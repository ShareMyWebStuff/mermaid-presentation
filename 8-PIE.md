## Pie Charts

Pie charts is produced using the following.

        ```mermaid
        pie showData
            title Key elements in Product X
            "Calcium" : 42.96
            "Potassium" : 50.05
            "Magnesium" : 10.01
            "Iron" :  5
        ```

This produces

```mermaid
%%{
    init: {
        'theme': 'base',
        'themeVariables': {
            'pieTitleSize': '25px',
            'pie1': '#BB2528',
            'pie2': '#006100',
            'pie3': '#444',
            'pie4': '#F8B229',
            'pie5': '#7C0000',
            'primaryColor': '#BB2528',
            'primaryTextColor': '#fff',
            'primaryBorderColor': '#7C0000',
            'lineColor': '#F8B229',
            'secondaryColor': '#006100',
            'tertiaryColor': '#444',
            'background': '#111'
        }
    }
}%%
pie showData
    title Key elements in Product X
    "Calcium" : 42.96
    "Potassium" : 50.05
    "Magnesium" : 10.01
    "Iron" :  5
```
