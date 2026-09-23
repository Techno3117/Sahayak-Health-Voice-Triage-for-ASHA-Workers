# Sahayak-Health-Voice-Triage-for-ASHA-Workers
Offline-first voice triage app for ASHA community health workers. Captures patient symptoms by voice in English or Hindi, classifies urgency (HIGH/MEDIUM/LOW), and stores records on-device — no internet, no backend, no build step.


Sahayak is a single-file, offline-first mobile web app built for ASHA (Accredited Social Health Activist) community health workers in rural India. It lets a worker record patient symptoms by voice — in English or Hindi — and instantly classifies urgency into four levels: HIGH (refer now), MEDIUM (same-day review), LOW (home care), or UNCERTAIN (consult doctor).

All processing runs on the device. No data leaves the phone during triage. Records are stored in localStorage and can be exported as JSON when connectivity returns.
