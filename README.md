# changes

## 2017-10-05
* New: (API) added lastBatchStatus command

## 2017-10-02
* Fixed: some scheduled traces would not be executed

## 2017-09-26
* Fixed: HipChat reporter can get stuck

## 2017-09-15
* New: (editor) while loop enabled for all
* New: (results) ability to switch the browser in the results view
* Fixed: (all traces) new tags not in search autocomplete until page refresh
* Fixed: (all traces) the results button sometimes disabled when there're results

## 2017-08-30
* New: ability to add multiple schedules
* New: (editor) While loop (beta)
* Fixed: reporter crash
* Fixed: sometimes browsers not released to the pool after system errors

## 2017-06-26
* New: (editor) file download step
* New: (editor) custom files (via File Download step)
* New: (editor) enhanced page history (meaningful page titles)
* Fixed: (recorder) SFDC picklists
* Fixed: (playback) "els not defined"
* Fixed: (firefox) disable geolocation prompt

## 2017-06-01
* New: (editor) Custom parameters can be defined in routine calls

## 2017-05-30
* Fixed: (editor) browsing routines while running a trace can result in Editor getting stuck in the "Running..." state
* Fixed: (backend) automatically retried sessions may show inconsistent results (for a short period)

## 2017-05-29
* Documentation screenshots updated to match current UI

## 2017-05-27
* New automatic variables BROWSER, BROWSER_NAME, BROWSER_VERSION
* Various optimizations in the infrastructure

## 2017-05-03
* Fixed: (playback) file dialog remains open in some edge cases
* Fixed: (recorder) can't check a disabled input field
* Optimizations to speed up the Usetrace browser infrastructure
* Improved DNS performance
* IEs updated to Selenium 2.53.1

## 2017-04-12
* Fixed: a subset of trial users unable to access the subscription page

## 2017-04-02
* New: (chrome playback) auto-allow notification dialogs

## 2017-03-29
* New: random text support for text locators
* New: session log to include steps' task boundaries
* Fixed: random replacement in checks attempted for longest match first
* Fixed: enabling a condition in a check step may break the check step
* Fixed: file upload playback sometimes throws an error with custom upload UI widget
* Fixed: deleted trace can reappear
* Fixed: (editor) occassional "version creation failed"
* Fixed: (editor) 'run this step' button sometimes in wrong state when a trace is running

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
