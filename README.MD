# flowcov-viewer

This library is a small viewer for the process coverage reports generated by [Camunda BPM Process Test Coverage](https://github.com/camunda-community-hub/camunda-bpm-process-test-coverage).

To use it, just copy the build output (index.html and static folder) and replace the placeholder `{{__REPORT_JSON_PLACEHOLDER__}}` in the index.html file with the report JSON. Then you can open the file.

![Generated Report](static/screenshot.png)
