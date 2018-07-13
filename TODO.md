+ Add flag to edit bookmarks in text editor when merging, or even after
  the fact. For example, open a text editor with

```
001 default_bookmark_name_1
009 default_bookmark_name_2
011 default_bookmark_name_3
211 default_bookmark_name_4
```

where the number represents the page number a bookmark is attached to.
The user could edit like so

```
001 new_name
009 default_bookmark_name_2
011 default_bookmark_name_3
212 new_name_and_page
```

and this could even support fancy nested bookmarking like

```
001 new_name
009    nested_name
011    another_nested_name
212 new_name_and_page
```

where the indentation (whitespace) indicates the nested bookmarks.
