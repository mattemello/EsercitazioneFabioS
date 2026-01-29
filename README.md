# Read this
[Passaggi](Passaggi.md)

[Creazione Database](CreareDb.sql)

```cshtml
@if (!ViewData.ModelState.IsValid) {
    @Html.ValidationSummary(false, "", new { @class = "alert alert-danger" })
}
```

``` webConfig
 <authentication mode="Forms">
     <forms loginUrl="~/User/Login" timeout="30"/>
 </authentication>
```
