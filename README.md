# TMDL  DimCalendario / DimDate  


> ![pt-BR](https://img.shields.io/badge/🇧🇷-pt--BR-FFDF00?style=flat&labelColor=009C3B)  
> Copie o código [DimCalendario_pt-BR.tmdl](DimCalendario_pt-BR.tmdl) cole na guia TMDL view e aplique.

> ![en-US](https://img.shields.io/badge/🇺🇸-en--US-B31942?style=flat&labelColor=0A3161)  
> Copy the code [DimDate_en-US.tmdl](DimDate_en-US.tmdl) and paste it into the TMDL view and apply.  

> ![es-ES](https://img.shields.io/badge/🇪🇸-es--ES-FFCC00?style=flat&labelColor=AA151B)  
> Copia el código [DimCalendario_es-ES.tmdl](DimCalendario_es-ES.tmdl), pégalo en la vista TMDL y aplícalo.  

--- 
> [!TIP]
> To remove the rows with `lineageTag` in the TMDL view in the Power BI Desktop.

Press CTRL + H  
Click on `.*`  
Fill `^\s*lineageTag:.*\r?\n`  
Press CTRL + ALT + ENTER

### Explanation
`^` → row start  
`\s*` → allow white spaces before lineageTag  
`lineageTag:` → search text  
`.*` → all after ":"  
`\r?\n` → line feed (Windows or Unix)  

---
[Announcement Power BI Blog](https://powerbi.microsoft.com/en-us/blog/power-bi-january-2025-feature-summary/)
