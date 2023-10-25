```html
<div class="form-group field-error">
  <label for="textarea">Label <span class="field-required">*</span></label>
  <div class="cmp-tooltip">
    <button type="button" aria-label="Help on textarea label" class="cmp-tooltip-btn">i</button>
    <div class="cmp-tooltip-content" role="status">
      <p hidden>Example and non-essential help about textarea</p>
    </div>
  </div>
  <p id="counter-textarea" role="status">
    <span class="counter-value">0</span>/
    <span class="counter-total">5000</span>
  </p>
  <textarea id="textarea" name="textarea" aria-describedby="desc-textarea counter-textarea error-textarea " aria-invalid="true"></textarea>
  <p id="desc-textarea">Help message</p>
  <p id="error-textarea" class="error">Error message</p>
</div>
```