# Tests

## Folder Structure

- The **fixtures** folder contains sample data, so there's something to test.
- The **source (src)** folder contains the actual test files. The subfolders emulate the real source folder's contents.
- **Test-Utils** stores any reusable functions for the test files. Each file has a corresponding test file.

### Extra

These _test_ files don't correlate to any _src_ files

- test/src/
  - \_getNewTemplateForTests.js
  - DependencyGraphTest.js
  - UserDataExtensionsTest.js
  - TemplateMapTest-ComputedData.js
  - TemplateTest-ComputedData.js
  - TemplateTest-JavaScript.js

### Missing

These _src_ files have no corresponding _test_ file

- src/
  - BenchmarkGroup.js
  - BenchmarkManager.js
  - Config.js
  - defaultConfig.js
  - EleventyBaseError.js
  - TemplateContent.js
  - Errors/
    - TemplateContentPrematureUseError.js
    - UsingCircularTemplateContentReferenceError.js
  - Filters/
    - Slug.js
  - Util/
    - GetJavaScriptData.js
