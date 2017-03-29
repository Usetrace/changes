# changes

## 2017-03-29
* New: random text support for text locators
* New: session log to include steps' task boundaries
* Fixed: random replacement in checks attempted for longest match first
* Fixed: enabling a condition in a check step may break the check step
* Fixed: file upload playback sometimes throws an error with custom upload UI widget

## 2017-03-13
* New: changes to traces synced automatically between users (no page reload needed)
* Fixed: new traces not sorted correctly by modification time in tracelist

## 2017-03-02
* New: invite team members to project

## 2017-02-19
* Fixed: (playback) leading/trailing whitespace confuses setElementSelected step
* Browsermob upgraded to 2.1.4

## 2017-02-18
* Fixed: (editor) sometimes pointer does not appear, gets stuck in "wait..."

## 2017-02-17
* Fixed: (editor) recording mode auto-closes when removing 2nd to last step using 'undo'

## 2017-02-15
* New: (editor) text locator matches input placeholder text

## 2017-02-14
* Performance: enhanced network throughput between test browser and the app under test

## 2017-02-11
* New: (editor) variable step type
* Fixed: (playback) selecting an item containing quotes from a 'select' element fails
* Fixed: app doesn't load if Mixpanel is blocked (adblocker)
* Fixed: clicking an element fails if a fixed navi-element (top/bottom) blocks it  
* Fixed: forking a trace should not copy the description field
* Fixed: parameter tab UI when there're no parameters
* Performance: (api) increased throughput of calls to 'execute'

## 2017-01-15
* New: (editor) locate element by text
* New: (editor) record drag-and-drop (html5, jQueryUI)
* New: (dashboard) flush queue button to clean up project's trace queue
* Fixed: (reports) formatting bug: "1min 60s" -> "2min"
* Fixed: (editor) some step type names missing on hover
