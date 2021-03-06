<a name="dicts-external_dicts_dict"></a>

# Configuring an External Dictionary

The dictionary configuration has the following structure:

```xml
<dictionary>
    <name>dict_name</name>

    <source>
      <!-- Source configuration -->
    </source>

    <layout>
      <!-- Memory layout configuration -->
    </layout>

    <structure>
      <!-- Complex key configuration -->
    </structure>

    <lifetime>
      <!-- Lifetime of dictionary in memory -->
    </lifetime>
</dictionary>
```

- name – The identifier that can be used to access the dictionary. Use the characters `[a-zA-Z0-9_\-]`.
- [source](external_dicts_dict_sources.md#dicts-external_dicts_dict_sources) — Source of the dictionary.
- [layout](external_dicts_dict_layout.md#dicts-external_dicts_dict_layout) — Dictionary layout in memory.
- [structure](external_dicts_dict_structure.md#dicts-external_dicts_dict_structure) — Structure of the dictionary . A key and attributes that can be retrieved by this key.
- [lifetime](external_dicts_dict_lifetime.md#dicts-external_dicts_dict_lifetime) — Frequency of dictionary updates.

[Original article](https://clickhouse.yandex/docs/en/query_language/dicts/external_dicts_dict/) <!--hide-->
