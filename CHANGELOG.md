# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.1] - 2024-02-16

### Added
- gRPC [RemoteService](./services/remote_service.proto) definition with endpoints:
    * OpenGazeStream
    * PerformCalibration
    * ObserveEyeTrackerAvailability
- new message types used to operate `RemoteService` service

