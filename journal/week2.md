# Week 2 — Distributed Tracing

## Required Homework/Tasks

i did already installed and configured the elk stack with a spring boot app, the main reason why is to mainly centralize my log in one app, 
i think i was kind of applying observability without realy knowing the meaning, also i did read article that mention OpenTelemetry, know i kind understand 
why it's used for.

### Instrument Honeycomb with OTEL	

i did watch the video and i tried to add the backend app to honeyComb

![instrument-honeyComb-otel][instrument-honeyComb-otel]

### Instrument AWS X-Ray

i did also try to apply the instruction in the video about x-ray, i do believe honeycomb give an easier experience specially for started,
also with aws ui that is always changing, honeycomb appear to be a better choice, but may be it does offer more functionality, also as
it's an AWS tools, it's easier to integrate because we don't need an other external app or tool to make observality work if we already using AWS

![instrument-x-ray][instrument-x-ray]


### Configure custom logger to send to CloudWatch Logs

![custom-logger-cloudwatch][custom-logger-cloudwatch]

### Integrate Rollbar and capture and error

i do think using Rollbar to centralize log in a simple ui make development easier by  facilitating the debug and detection of the problem,
specially if we use Rollbar notifications to alert developer when error happens

![integrate-rollbar][integrate-rollbar]

![integrate-rollbar-apicall-loop][integrate-rollbar-apicall-loop]


[instrument-honeyComb-otel]: assets/instrument-honeycomb-otel.png
[instrument-x-ray]: assets/Instrument-AWS-X-Ray.png
[custom-logger-cloudwatch]: assets/custom-logger-cloudwatch.png
[integrate-rollbar]: assets/integrate-rollbar.png
[integrate-rollbar-apicall-loop]: assets/integrate-rollbar-apicall-loop.png