```html 
//DesignSystem version 2023
<fieldset class="form-options form-options--checkbox field-error" aria-invalid="true" aria-describedby="desc-checkbox error-checkbox">
  <legend class="form-options-legend">
    Legend <span class="field-required">*</span>
    <div class="tooltip">
      <button type="button" aria-label="Help message about this field" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Non-essential help message</p>
      </div>
    </div>
  </legend>
  <div class="alert alert--info">
    <p id="desc-checkbox">Help message</p>
  </div>
  <ul class=" form-options-content">
    <li class="form-options-group">
      <label class="form-options-label" for="checkbox1">
        <input class="form-options-field form-options-field--checkbox" name="checkbox1" id="checkbox1" type="checkbox">
        <span class="form-options-description">Label 1</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="checkbox2">
        <input class="form-options-field form-options-field--checkbox" name="checkbox2" id="checkbox2" type="checkbox">
        <span class="form-options-description">Label 2</span>
      </label>
    </li>
    <li class="form-options-group">
      <label class="form-options-label" for="checkbox3">
        <input class="form-options-field form-options-field--checkbox" name="checkbox3" id="checkbox3" type="checkbox">
        <span class="form-options-description">Label 3</span>
      </label>
    </li>
  </ul>
  <div class="alert alert--error">
    <p id="error-checkbox" class="error">Error message</p>
  </div>
</fieldset>

```
