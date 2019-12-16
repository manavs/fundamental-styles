---
title: Combobox Input
id: combobox-input
keywords: combobox input
sidebar: left-navigation-sidebar
toc: false
permalink: patterns/combobox-input.html
folder: patterns
summary:
---

The combobox input component is an opinionated composition of the `input group`, `popover` and `menu` components with the use of a styled button.
{: .docs-intro}

{% capture default %}
<div class="documentation-site-popover-container">
  <div class="fd-popover">
      <div class="fd-popover__control fd-input-group__control" aria-controls="F4GcX348" aria-expanded="false" aria-haspopup="true">
          <div class="fd-input-group">
              <input type="text" class="fd-input fd-input-group__input" id="" placeholder="Select Fruit">
              <span class="fd-input-group__addon fd-input-group__addon--button">
                  <button class="fd-input-group__button fd-button--light sap-icon--navigation-down-arrow fd-select__button"></button>
              </span>
          </div>
      </div>
      <div class="fd-popover__body fd-popover__body--no-arrow" aria-hidden="true" id="F4GcX348">
            <ul class="fd-dropdown-list" role="listbox">
                <li class="fd-dropdown-list__item is-selected" role="option">
                  <span href="#" class="fd-dropdown-list__title">List item 1</span>
                </li>
                <li class="fd-dropdown-list__item" role="option">
                  <span href="#" class="fd-dropdown-list__title">List item 2</span>
                </li>
                <li class="fd-dropdown-list__item" role="option">
                  <span href="#" class="fd-dropdown-list__title">List item 3</span>
                </li>
                <li class="fd-dropdown-list__item" role="option">
                  <span href="#" class="fd-dropdown-list__title">List item 4</span>
                </li>
            </ul>
      </div>
  </div>
</div>

<br>

<div class="documentation-site-popover-container">
  <div class="fd-popover">
      <div class="fd-popover__control fd-input-group__control" aria-controls="F4GcX34" aria-expanded="false" aria-haspopup="true">
                <div class="fd-input-group">
                    <input type="text" class="fd-input fd-input--compact fd-input-group__input" id="" placeholder="Select Fruit">
                    <span class="fd-input-group__addon fd-input-group__addon--compact fd-input-group__addon--button">
                        <button class="fd-input-group__button fd-button--compact fd-button--light sap-icon--navigation-down-arrow fd-select__button"></button>
                    </span>
                </div>
            </div>
      <div class="fd-popover__body fd-popover__body--no-arrow" aria-hidden="true" id="F4GcX34">
            <ul class="fd-list fd-list--no-border" role="listbox">
                <li class="fd-list__item is-selected" role="option">
                    <span href="#" class="fd-list__title">List item 1</span>
                </li>
                <li class="fd-list__item" role="option">
                    <span href="#" class="fd-list__title">List item 2</span>
                </li>
                <li class="fd-list__item" role="option">
                    <span href="#" class="fd-list__title">List item 3</span>
                </li>
                <li class="fd-list__item" role="option">
                    <span href="#" class="fd-list__title">List item 4</span>
                </li>
            </ul>
      </div>
  </div>
</div>
{% endcapture %}
{% include display-component.html component=default %}
