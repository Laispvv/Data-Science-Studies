# Convertendo e Formatando Dados

## Convertendo Dados em Planilhas

-  String ➡️ Date
   -  [Excel](https://www.ablebits.com/office-addins-blog/2015/03/26/excel-convert-text-date/#:~:text=Excel%20DATEVALUE%20function%20%2D%20change%20text,Excel%20recognizes%20as%20a%20date.&text=So%2C%20the%20formula%20to%20convert,stored%20as%20a%20text%20string.)
   -  [Google Sheets](https://www.ablebits.com/office-addins-blog/google-sheets-change-date-format/)
-  String ➡️ Número
   -  [Excel](https://www.ablebits.com/office-addins-blog/2018/07/18/excel-convert-text-to-number/)
   -  [Google Sheets](https://productivityspot.com/convert-text-to-numbers-google-sheets/)
-  Número ➡️ Porcentagem
   -  [Excel](https://support.microsoft.com/en-us/office/format-numbers-as-percentages-de49167b-d603-4450-bcaa-31fba6c7b6b4)
   -  [Google Sheets](https://support.google.com/docs/answer/3094284?hl=en)
-  Combinando Colunas
   -  [Excel](https://support.microsoft.com/en-us/office/combine-text-from-two-or-more-cells-into-one-cell-81ba0946-ce78-42ed-b3c3-21340eb164a6)
   -  [Google Sheets](https://www.techrepublic.com/article/how-to-split-or-combine-text-cells-with-google-sheets/)

## Convertendo Dados em SQL

Para converter dados em SQL usamos as funções CAST ou SAFE_CAST, em que:
- **CAST** retorna um erro caso não consiga converter
- **SAFE_CAST** retorna NULL nos campos em que não conseguir converter

A sintaxe de uso é a seguinte:
```sql
SELECT CAST(MyDate AS STRING) FROM MyTable
```

[Mais informações sobre Type Casting do SQL](https://rudderstack.com/guides/how-to-sql-type-casting/)