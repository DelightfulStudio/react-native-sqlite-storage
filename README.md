# Fork of [react-native-sqlite-storage](https://github.com/andpor/react-native-sqlite-storage)

Major changes:
 - `libsqlite3.0` is no longer auto-linked when you run `react-native link`; this enables linking with a custom SQLite static library, e.g. https://github.com/swiftlyfalling/SQLiteLib
 - Better logging of errors
