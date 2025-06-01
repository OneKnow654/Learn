

## ✅ `README.md` — Cron Job Tutorial


# ⏰ Linux Cron Job Guide

This is a quick reference to help you schedule and manage automated tasks on Linux using **cron**.



## 📖 What is Cron?

Cron is a time-based job scheduler in Unix-like operating systems. It allows you to run commands or scripts automatically at specified intervals.

---

## 🔧 How to Use

### Step 1: Open the Crontab Editor

```bash
crontab -e
````

### Step 2: Add a Cron Job

```bash
* * * * * /path/to/your/script.sh
```

This means: run the script **every minute**.

---

## 🕓 Cron Timing Format

```
* * * * *  command_to_run
│ │ │ │ │
│ │ │ │ └── Day of the week (0 - 7) (Sunday = 0 or 7)
│ │ │ └──── Month (1 - 12)
│ │ └────── Day of the month (1 - 31)
│ └──────── Hour (0 - 23)
└────────── Minute (0 - 59)
```

---

## 🔁 Examples

| Schedule                 | Cron Syntax               |
| ------------------------ | ------------------------- |
| Every minute             | `* * * * *`               |
| Every 5 minutes          | `*/5 * * * *`             |
| Every day at 5:00 PM     | `0 17 * * *`              |
| Every Monday at midnight | `0 0 * * 1`               |
| On boot (special)        | `@reboot /path/script.sh` |

---


> Use cron tab generate -> [here](https://crontab.cronhub.io/)

## 🛠 Example: Auto Bash Script

Create a file `myjob.sh`:

```bash
#!/bin/bash
echo "Task ran at $(date)" >> ~/cron_log.txt
```

Make it executable:

```bash
chmod +x myjob.sh
```

Add to cron:

```bash
crontab -e
```

Then insert:

```cron
*/1 * * * * /full/path/to/myjob.sh
```

---

## 📜 View & Manage Cron Jobs

* List your jobs: `crontab -l`
* Edit your jobs: `crontab -e`
* Remove all jobs: `crontab -r`

---

## 📍 Where Is Output Stored?

By default, cron jobs **send output to your mail**.
To log output manually:

```cron
*/1 * * * * /path/script.sh >> ~/cron_output.log 2>&1
```

---

## 🧪 Test Tips

* Use `date` inside your script to confirm it's running.
* Log to a file like `~/cron_test.log` to capture output.

---

## ✅ Checklist for Cron Jobs to Work

* [x] Script is executable: `chmod +x script.sh`
* [x] Full path is used (cron has no PATH): e.g., `/usr/bin/python3`
* [x] Script has `#!/bin/bash` at top
* [x] Use full paths for any commands or files in your script



---

## 🛠 `myjob.sh` — Sample Bash Script to Schedule

```bash
#!/bin/bash
# This script logs the current time to a file

echo "Cron ran at: $(date)" >> ~/cron_output.log
````

> Make it executable:

```bash
chmod +x myjob.sh
```

---

## ✅ Add It to Cron

```bash
crontab -e
```

Then add:

```cron
*/1 * * * * /full/path/to/myjob.sh
```

---

