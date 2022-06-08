# PHP + [OpenTelemetry](https://opentelemetry.io) demo

Demo of __Application Performance Monitoring (APM)__ for PHP Application using OpenTelemetry traces.

## Usage

Start the application and APM backends by running:
```shell
docker-compose up
```

Make some requests http://localhost:8080/ and then check APM backend(s) for traces:
- Jaeger: http://localhost:16686/  
- Zipkin: http://localhost:9411/
