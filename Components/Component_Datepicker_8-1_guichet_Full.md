```html
<div class="form-group field-error">
  <label for="date">Label <span class="field-required">*</span></label>
  <div class="cmp-tooltip">
    <button type="button" aria-label="Help on date label field" class="cmp-tooltip-btn">i</button>
    <div class="cmp-tooltip-content" role="status">
      <p>Example and non-essential help about date label field</p>
    </div>
  </div>
  <input id="date" name="datefield" type="date" aria-describedby="desc-date error-date" aria-invalid="true">
  <div class="alert alert--info">
    <p id="desc-date">Help message</p>
  </div>
  <div class="alert alert--error">
    <p id="error-date" class="error">Error message</p>
  </div>
</div>
```