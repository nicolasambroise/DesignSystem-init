```html
<div class="form-group field-error">
  <label for="textfield">Label <span class="field-required">*</span></label>
  <div class="cmp-tooltip">
    <button type="button" aria-label="Help on textfield label" class="cmp-tooltip-btn">i</button>
    <div class="cmp-tooltip-content" role="status">
      <p>Example and non-essential help about this textfield</p>
    </div>
  </div>
  <p id="counter-textfield" role="status" aria-live="polite" aria-atomic="true">
    <span class="counter-value">0</span>/
    <span class="counter-total">12</span>
  </p>
  <div class="from-field-wrapper--suffix">
    <input type="text" id="textfield" name="textfield" class="form-field" aria-invalid="true" aria-describedby="desc-textfield suffix-textfield counter-textfield error-textfield" required>
    <p id="suffix-textfield" class="form-field-suffix">
      <span aria-hidden="true">€</span>
      <span class="sr-only">amount in euros</span>
    </p>
  </div>
  <div class="alert alert--info">  
    <p id="desc-textfield">Help message</p>
  </div>
  <div class="alert alert--error">  
    <p id="error-textfield" class="error">Error message</p>
  </div>
</div>
```
