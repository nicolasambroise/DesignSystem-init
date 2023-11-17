```html
<fieldset class="cmp-form-options cmp-form-options--checkbox field-error" aria-invalid="true" aria-describedby="desc-checkbox error-checkbox">
  <legend class="cmp-form-options__legend">
    Legend <span class="field-required">*</span>
    <div class="cmp-tooltip">
      <button type="button" aria-label="Help message about this field" class="cmp-tooltip-btn">i</button>
      <div class="cmp-tooltip-content" role="status">
        <p>Non-essential help message</p>
      </div>
    </div>
  </legend>
  <div class="alert alert--info">
    <p id="desc-checkbox">Help message</p>
  </div>
  <ul class=" cmp-form-options__content">
    <li class="cmp-form-options__group">
      <label class="cmp-form-options__field-label" for="checkbox1">
        <input class="cmp-form-options__field cmp-form-options__field--checkbox" name="checkbox1" id="checkbox1" type="checkbox">
        <span class="cmp-form-options__field-description">Label 1</span>
      </label>
    </li>
    <li class="cmp-form-options__group">
      <label class="cmp-form-options__field-label" for="checkbox2">
        <input class="cmp-form-options__field cmp-form-options__field--checkbox" name="checkbox2" id="checkbox2" type="checkbox">
        <span class="cmp-form-options__field-description">Label 2</span>
      </label>
    </li>
    <li class="cmp-form-options__group">
      <label class="cmp-form-options__field-label" for="checkbox3">
        <input class="cmp-form-options__field cmp-form-options__field--checkbox" name="checkbox3" id="checkbox3" type="checkbox">
        <span class="cmp-form-options__field-description">Label 3</span>
      </label>
    </li>
  </ul>
  <div class="alert alert--error">
    <p id="error-checkbox" class="error">Error message</p>
  </div>
</fieldset>

```
