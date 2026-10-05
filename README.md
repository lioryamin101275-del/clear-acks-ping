# clear-acks-ping

Every 5 minutes this repo's GitHub Action calls the WhatsApp agent's `/api/cron/acks`,
so automatic replies go out even when Lior's computer is off.
The URL is stored as an encrypted Actions secret (`ACKS_URL`); nothing sensitive is in this repo.
