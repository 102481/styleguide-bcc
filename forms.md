# Forms
Council's corporate website has the capacity to build and host online forms. These forms are fully compliant with Council's accessibility commitments (WCAG 2.0 AA) and are fully mobile responsive. 

These forms offer a full array of modern online form features, including conditional logic. 

## Text Input
Text inputs allow people to enter any combination of letters, numbers, or symbols of their choosing (unless otherwise restricted). Text input boxes can span single or multiple lines.

###Text input label
```
<input required="required" type="text" 
id="edit-submitted-incident-street-address" value="" size="60" 
maxlength="128" class="form-text required">
```

<input type="text" value="" size="60" maxlength="128" class="form-text">

###Active text input label
<input type="text" value="" size="60" maxlength="128" class="form-text focus">

###Text input error
<input type="text" value="" size="60" maxlength="128" class="form-text error">

###Text Area
<textarea cols="60" rows="5" class="form-textarea"></textarea><div class="grippie"></div>


## Dropdown
A dropdown allows users to select one option from a list.

###Drop down menu

```
<select>
    <option value="" selected="selected">- Select -</option>
    <option value="Cat">Feral Cat</option>
    <option value="Dog">Wild Dog</option>
    <option value="Fox">European red fox</option>
    <option value="Deer">Feral deer</option>
    <option value="Rabbit">Rabbit</option>    
</select>
```
<select class="form-select">
    <option value="" selected="selected">- Select -</option>
    <option value="Cat">Feral Cat</option>
    <option value="Dog">Wild Dog</option>
    <option value="Fox">European red fox</option>
    <option value="Deer">Feral deer</option>
    <option value="Rabbit">Rabbit</option>    
</select>


## Checkboxes
Checkboxes allow users to select one or more options from a visible list.

```
<input type="checkbox" value="damaged_surface" class="form-checkbox">
<label class="option">Damaged surface </label>

```
<input type="checkbox" value="damaged_surface" class="form-checkbox"> <label class="option">Damaged surface</label>


## Radio Buttons
```
<input type="radio" value="yes" class="form-radio">
<label class="option">Yes</label>
<input type="radio" value="no" class="form-radio">
<label class="option">No</label>

```
<div class="form-item">
<input type="radio" value="yes" class="form-radio">
<label class="option">Yes</label>
</div>
<div class="form-item">
<input type="radio" value="no" class="form-radio">
<label class="option">No</label>
</div>

## Date Input

## Attachments
File attachment input
```
<input type="file" size="22" class="form-file">
```
<input type="file" size="22" class="form-file">
<input type="submit" class="form-submit">

## Form elements
