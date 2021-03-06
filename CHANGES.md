# Change Log

## 0.21.3
- Rebuilt with OSX 10.9 Python 3.7

## 0.21.2
- Remove more references to syslog

## 0.21.1
- Fix crashing on OSX 10.12 when built with 10.13

## 0.21.0
- Fix window sticking on top when it shouldn't
- Add semi colon as delimiter

## 0.20.2
- Fix issue when row contains few columns than headers

## 0.20.0
- Stop supporting Python 2!!!
- Allow delimiter to be selected in UI
- Restrict delimiter detection to comma, tab and bar
- Add left click column to sort it
- Fix sort indicator when removing filters

## 0.14.0
- Copy as SQL IN
- Copy as Array
- More error handling
- More lenient encoding rules

## 0.13.1
- Fix zoom positioning

## 0.13.0
- Optimize Font Zooming

## 0.12.1
- Fix opening UTF-16 files

## 0.12.0
- Show open grids in Window menu

## 0.11.1
- Fix <enter> behavior in search box

## 0.11.0
- Handle size arguments via --size
- Set busy cursor when loading data

## 0.10.0
- Move aggregates to bottom status text

## 0.9.0
- Option to copy headers
- Show simple aggregates of the current selection

## 0.8.1
- Handle headers with illegal characters

## 0.8.0
- Align numeric columns to the right (Issue #5)
- Open frame in active display
- Ensure grid cell is selected after click
- Fixed connection errors between main and background thread
- Fix row index synchronization. (Issue #8)

## 0.7.3
- drop Pandas due to incompatibilities with py2app

## 0.7.0
- dropped support for Python 2.7
  - for use of lru_cache
- import into SQLite3 database to reduce memory use
  - removed regexp search across columns
- use Pandas for CVS parsing and type matching

## 0.6.0
- Add search across columns
