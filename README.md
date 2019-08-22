# android-analytics-testing
Various notes to help test what various analytics providers report.

Providers include Google Play with the bundled Android Vitals, crash analytics, mobile analytics, and heatmapping offerings.

## Testing Cycle
Tests need to be structured in order to make comparisons useful and trustworthy. Here is an outline of an initial test process.

1. Record: details of the planned test so we keep the objective in focus and have a record post-hoc
2. Preparation: for instance of Android devices, configuring accounts, configuring device settings (e.g. locale), connectivity, installing apps and related data, etc.
3. Connection: between the device under test and any controller and to the network/Internet if that's needed for the test
4. Synchronisation: of the timings and date-times, timezones, etc. Co-ordinating parallel activities including multiple devices, test/log recordings, logging into monitoring systems, etc.
5. Test execution and validation: Running the tests and checking them while they are running to catch problems that would affect the validity of the test e.g. broken permissions, failing connectivity, external factors that intrude on the testing, etc.
6. Collection: of data, logs, screenshots, and other evidence. This may need to happen within a short period for transitory reports that update regularly, etc.
7. Analysis: of what has been collected and initial findings & interpretation.
8. Archiving/Logging: of relevant subset of what has been collected.
9. Clean-up: temporary logs, particularly any sensitive data, tidy-up, etc.
