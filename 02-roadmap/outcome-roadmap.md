# Outcome Roadmap & Trade-off Memo: Meridian Foundations

> Module 2 · Turn Your Strategy into an Outcome Roadmap

## 1. Trade-off memo

> **Rock 1:** Add real-time weather data to the scheduling module (supports KR2): Reduces the mental load, since it allows to plan more accurately
>
> **Rock 2:** Enable push notifications for schedule changes (supports KR3): Reduces the need for communication and coordination since everyone is informed automatically
>
> **Rock 3:** Add a photo markup and annotation tool for field teams (supports KR2): pulls the users into the Meridian ecosystem
>
> **Hard no 1:** Fix the Procore import/export integration (broken for 2 clients): low impact at only two customers
>
> **Hard no 2:** Refresh the web UI (feedback: “looks outdated” from prospects): usability seems not to be affected.
>
> **Hard no 3:** Migrate the data model to support multi-project dashboards: large project with high effort and unclear benefit.

## 2. Outcome roadmap

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| Now (0 to 3 mo) | Horizon	Outcome / bet	Owning team(s)	Success signal Now (0 to 3 mo)	(1) KR1: We bet making the daily log quicker to complete than a group-chat message will make daily logging routine on 40% of active projects, for superintendents at top-100 GCs (tested with auto-filled weather); (2) KR2: We bet letting crews show a site issue instead of typing it out will make Meridian their default way to report issues, so active field users per project grow from 5% to 40%, for foremen and field crews (tested with photo markup); (3) KR3: We bet getting crews into Meridian at the moment the plan changes will move log capture from the office to the job site, so mobile on-site capture grows from 10% to 50%, for foremen on top-100 GC projects (tested with schedule-change push notifications)	(1) Scheduling + Field Logs; (2) Mobile / Field Experience; (3) Mobile + Notifications	(1) Median time to log drops by at least 30%, and projects with daily logs go from 10% to 40%; (2) issues reported in Meridian instead of the group chat go up, and active field users per project go from 5% to 40%; (3) at least 25% of notification opens lead to an on-site log the same day, and mobile on-site capture goes from 10% to 50% Next (3 to 6 mo)	Offline-first capture and sync, because Now will show where weak site connectivity drops data; field-to-office data routing into customers’ project-management and ERP systems, because it’s only worth fixing once enough logs are coming in; one-tap access for subcontractors (SMS link, no account setup), because the core loop has to stick before we scale who uses it; a multi-site daily-log rollup for office and execs, because it needs log coverage to be meaningful; an adoption playbook per customer tier (starting with the 38 customers where Meridian is the system of record), because it reuses what worked in Now	Platform / Sync; Integrations; Growth + Identity; Office / Analytics; Customer Success + Sales	Fewer lost or late logs; logs reaching office systems with no re-keying; more subcontractor users per project; execs using the rollup each week; adoption KPIs hit in each tier Later (6 to 12 mo), bets not commitments	Bet: a daily log drafted automatically from voice and photos; Bet: bringing WhatsApp and SMS messages into Meridian, so it captures what crews already send; Bet: predicting schedule risk from weather and log data across all customers; Bet: field-adoption proof as the sales story for new top-100 logos	AI / Data; Integrations; Data Science; Sales + Marketing	The draft log gets accepted with few edits; the share of group-chat traffic captured; how accurate the risk predictions are; the win rate on new top-100 logos | _____ | _____ |
| Next (3 to 6 mo) | _____ | _____ | _____ |
| Later (6 to 12 mo) | _____ | _____ | _____ |
