It's a service to run a schedule "batch" job, with a start and an end.

The service will dynamically launch [[AWS EC2]] instances or [[AWS EC2 Instances Purchasing Options#4. **Spot instances**|spot instances]].

The main difference between Batch and [[AWS Lambda]] functions are:

1. No time limit
2. Rely on [[AWS EBS Volume]] for disk space, whereas [[AWS Lambda]] has limited temporary disk space.
3. Relies on [[AWS EC2]] instances, whereas [[AWS Lambda]] is [[serverless]].
