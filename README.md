# Selenium-Utils
# Documentation

## `public class Utility`

<b>Collection of all the Generic Selenium methods.</b><br> To reduce coding effort and reuse the methods</b>

 * **Author:** Chandrashekhar Gouda
 * **Version:** 1.0
 * **Since:** 2018-10-17

## `public static WebDriver driver = null`

The Web Driver.

## `public static WebDriver OpenApp(String BrowserName, String url)`

Open app.

 * **Parameters:**
   * `BrowserName` — the browser name
   * `url` — the url
 * **Returns:** the web driver

## `public static void OpenURL(String url)`

Open URL.

 * **Parameters:** `url` — the url

## `public static WebDriver LaunchBrowser(String browsername)`

Launch browser.

 * **Parameters:** `browsername` — the browsername
 * **Returns:** the web driver

## `public static void Wait(By path)`

Wait Until element found.

 * **Parameters:** `path` — path of the element

## `public static void Wait(By path, int sec)`

Wait Until element found.

 * **Parameters:** `path` — path of the element

## `public static void Click(By path)`

Click on the element.

 * **Parameters:** `path` — path of the element

## `public static void ClickParentElement(By path)`

Click parent element.

 * **Parameters:** `path` — the path

## `public static void SendKeys(By path, String inputValue)`

Send Keys to input box.

 * **Parameters:**
   * `path` — path of the element
   * `inputValue` — the input value

## `public static WebDriver getDriver()`

Gets the web driver.

 * **Returns:** the web driver.

## `public static void SwitchToChildWindow()`

Switch to child window.

## `public static void MouseOver(By path)`

Mouse over on the element.

 * **Parameters:** `path` — path of the element

## `public static void DropdownSelectByText(By path, String VisibleText)`

Drop down select by text.

 * **Parameters:**
   * `path` — path of the element
   * `VisibleText` — the visible text

## `public static void MultiSelectByText(By path, String[] VisibleTexts)`

Multi select by text.

 * **Parameters:**
   * `path` — path of element
   * `VisibleTexts` — the visible options text

## `public static void DropdownSelectByIndex(By path, int IndexValue)`

Drop down select by index.

 * **Parameters:**
   * `path` — path of the element
   * `IndexValue` — the index value

## `public static void MultiSelectByIndex(By path, int[] IndexValues)`

Multi select by index.

 * **Parameters:**
   * `path` — path of element
   * `IndexValues` — the index values of options

## `public static void DropdownSelectByValue(By path, String Value)`

Drop down select by value.

 * **Parameters:**
   * `path` — path of the element
   * `Value` — the value

## `public static void MultiSelectByValues(By path, String[] Values)`

Multi select by values.

 * **Parameters:**
   * `path` — path of the element
   * `Values` — the options value

## `public static void DeselectOptions(By path)`

Deselect all options .

 * **Parameters:** `path` — path of element

## `public static void MultiSelectAll(By path)`

Multi select all.

 * **Parameters:** `path` — the path

## `public static String GetText(By path)`

Gets the text from the element.

 * **Parameters:** `path` — path of the element
 * **Returns:** the Text

## `public static void confirmPopup(String status, String expectedtxt) throws InterruptedException`

Confirm popup/Alert of IBO*ARM.

 * **Parameters:**
   * `status` — the status
   * `expectedtxt` — the expectedtxt
 * **Exceptions:** `InterruptedException` — the interrupted exception

## `public static boolean isElementPresent(By path)`

Checks is element present.

 * **Parameters:** `path` — path of the element
 * **Returns:** true, if is element present

## `public static int ElementCounter(By path)`

Element Counter.

 * **Parameters:** `path` — path of the element
 * **Returns:** size the elements size

## `public static String getColor(By path)`

Gets the color of text.

 * **Parameters:** `path` — path of element of element
 * **Returns:** the color

## `public static String getClass(By path)`

Gets the class element.

 * **Parameters:** `path` — path of element of element of element
 * **Returns:** the class

## `public static boolean isDisplayed(By path)`

Checks if is displayed.

 * **Parameters:** `path` — path of element of element
 * **Returns:** true, if is displayed

## `public static boolean isEnabled(By path)`

Checks if is enabled.

 * **Parameters:** `path` — path of element of element
 * **Returns:** true, if is enabled

## `public static boolean isSelected(By path)`

Checks if is selected.

 * **Parameters:** `path` — path of element of element
 * **Returns:** true, if is selected

## `public static void submit(By path)`

Submit the form.

 * **Parameters:** `path` — path of element

## `public static String getPageTitle(By path)`

Gets the page title.

 * **Parameters:** `path` — path of element
 * **Returns:** the page title

## `public static String getCurrentUrl(By path)`

Gets the current url.

 * **Parameters:** `path` — path of element
 * **Returns:** the current url

## `public static void refreshPage()`

Refresh the current page.

## `public static String getCssValue(By path, String cssProperty)`

Gets the css value.

 * **Parameters:**
   * `path` — path of element
   * `cssProperty` — the css property
 * **Returns:** the css value

## `public static String getAttribute(By path, String attribute)`

Gets the attribute.

 * **Parameters:**
   * `path` — path of element
   * `attribute` — the attribute
 * **Returns:** the attribute value

## `public static void quitDriver()`

Closes the driver.

## `public static String getValue(By path)`

Get value by Attribute .

## `public static void ClearField(By path)`

Clear Field value .

## `public static void ClearField2(By path)`

Clear Field value .

## `public static void WaitUntilDisappear(By path, int second)`

Wait until disappear.

 * **Parameters:**
   * `path` — the path
   * `second` — the second

## `public static void insertText(By path, String inputValue)`

Appends text to input box .

 * **Parameters:**
   * `path` — path of the element
   * `inputValue` — the input value

## `public static int DropdownSelectLenght(By path)`

Dropdown select lenght.

 * **Parameters:** `path` — the path

## `public static void ClickHiddenElement(By element) throws InterruptedException`

Click hidden element.

 * **Parameters:** `element` — the element
 * **Exceptions:** `InterruptedException` — the interrupted exception

## `public static void uploadfile(By path, String[][] uploadfile) throws InterruptedException`

Uploadfile.

 * **Parameters:** `path` — the path

## `public static List<String> getAllOptionsOfDropdown(By by)`

Gets the all options of dropdown.

 * **Parameters:** `by` — the by
 * **Returns:** the all options of dropdown
