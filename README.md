# Read this
[Passaggi](Passaggi.md)

[Creazione Database](CreareDb.sql)


@if (!ViewData.ModelState.IsValid) {
    @Html.ValidationSummary(false, "", new { @class = "alert alert-danger" })
}
