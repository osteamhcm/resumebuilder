## Language Resume Builder

Shared repository for open-sourced projects from the tool `Resume Builder Language`.

## Demo Tool Resume Builder, CV Builder

- Website: https://resume.melink.top
- Demo Admin Login: admin@admin.com
- Demo Admin Password: admin@admin.com
- Buy Tool: https://codecanyon.net/item/resume-builder/25370313


## HOW TO ADD NEW LANGUAGE?

1. Open /config/languages.php and add new language:

```

                'xx' => [
                  'name'     => 'Language name',
                  'native'   => 'Language native name',
                  'dir'      => 'ltr',
                  'regional' => 'xx_XX',
                ],
```
            
2. Copy folder `/resources/lang/en/` to `/resources/lang/xx/`
3. Copy file `/resources/lang/pt.json` to `/resources/lang/xx.json`
4. Make necessary translations.
