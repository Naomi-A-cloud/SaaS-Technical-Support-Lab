# INC-002: File Upload Service Degradation

## Incident Information

Incident ID: INC-002  
Severity: P2 - High  
Service: File Upload  
Status: Investigating

## Summary

Customers report intermittent failures when uploading files.

## Customer Impact

Some customers are unable to upload files successfully.

## Investigation

Support reviewed application and API behaviour.

Observed symptoms include:

- Failed upload attempts
- Increased response times
- Intermittent server errors

## Initial Assessment

The issue appears to be related to the backend upload service.

## Troubleshooting

- Reproduced upload failure
- Checked browser behaviour
- Tested multiple file types
- Reviewed API responses
- Reviewed application logs

## Escalation

The issue was escalated to Engineering for backend investigation.

## Current Status

Engineering investigation in progress.

## Next Actions

- Monitor upload-service errors
- Review backend logs
- Confirm service recovery
- Update affected customers
- Document root cause after resolution