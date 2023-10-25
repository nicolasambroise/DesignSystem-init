```html
<div class="form-group field-error">
  <label for="select">Label <span class="field-required">*</span></label>
  <div class="cmp-tooltip">
    <button type="button" aria-label="Help on select label" class="cmp-tooltip-btn">i</button>
    <div class="cmp-tooltip-content" role="status">
      <p hidden>Example and non-essential help about select</p>
    </div>
  </div>
  <select id="select" name="select" class="form-field" aria-describedby="desc-select error-select" aria-invalid="true" required>
    <option value="" selected disabled hidden>Select an option</option>
    <option value="option1">Option 1</option>
    <option value="option2">Option 2</option>
    <option value="option3">Option 3</option>
  </select>
  <p id="desc-select">Help message</p>
  <p id="error-select" class="error">Error message</p>
</div>
```
