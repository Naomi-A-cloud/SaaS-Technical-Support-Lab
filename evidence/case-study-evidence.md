# Case Study Evidence Map

## TICKET-008

Issue: HTTP 500 application error

Ticket:

`tickets/TICKET-008-http-500.md`

## Application Evidence

Log:

`logs/application.log`

Relevant evidence:

```text
2026-09-10 10:21:12 ERROR application Report generation failed service=report-service
2026-09-10 10:21:12 ERROR application HTTP response status=500 endpoint=/reports
2026-09-10 10:21:13 INFO application Error recorded request_id=req-84721