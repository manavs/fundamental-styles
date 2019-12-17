---
title: Multi Input
id: multi-input
keywords: multi input
sidebar: left-navigation-sidebar
toc: false
permalink: patterns/multi-input.html
folder: patterns
summary:
---


## Default and Compact sizes

{% capture default %}
<div class="fd-multi-input">
    <div class="fd-multi-input-field">
        <div class="fd-popover">
            <div class="fd-popover__control fd-input-group__control">
                <div aria-label="Image label" aria-controls="F4GcX348a" aria-expanded="false" aria-haspopup="true">
                    <div class="fd-input-group">
                        <input type="text" class="fd-input fd-input-group__input" id="" placeholder="Select Fruit">
                        <span class="fd-input-group__addon fd-input-group__addon--button">
                            <button class="fd-input-group__button fd-button--light sap-icon--value-help"></button>
                        </span>
                    </div>
                </div>
            </div>
            <div class="fd-popover__body fd-popover__body--no-arrow" aria-hidden="true" id="F4GcX348a">
                <ul class="fd-dropdown-list">
                     <li class="fd-multi-input__element" role="option">
                        <label class="fd-dropdown-list__item fd-multi-input__label is-selected" for="a1">
                            <input type="checkbox" class="fd-checkbox fd-multi-input__input" checked id="a1">
                            <span class="fd-dropdown-list__title">Apple</span>
                            <span class="fd-dropdown-list__secondary">A1</span>
                        </label>
                    </li>
                    <li class="fd-multi-input__element" role="option">
                        <label class="fd-dropdown-list__item fd-multi-input__label" for="b1">
                            <input type="checkbox" class="fd-checkbox fd-multi-input__input" id="b1">
                            <span class="fd-dropdown-list__title">Berry</span>
                            <span class="fd-dropdown-list__secondary">B1</span>
                        </label>
                    </li>
                    <li class="fd-multi-input__element" role="option">
                       <label class="fd-dropdown-list__item fd-multi-input__label" for="c1">
                           <input type="checkbox" class="fd-checkbox fd-multi-input__input" id="c1">
                           <span class="fd-dropdown-list__title">Banana</span>
                           <span class="fd-dropdown-list__secondary">C1</span>
                       </label>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    <div class="fd-multi-input-tags">
        <span class="fd-token" role="button">Apple</span>
        <span class="fd-token" role="button">Berry</span>
        <span class="fd-token" role="button">Banana</span>
    </div>
</div>

<br>

<div class="fd-multi-input">
    <div class="fd-multi-input-field">
        <div class="fd-popover">
            <div class="fd-popover__control fd-input-group__control">
                <div aria-label="Image label" aria-controls="F4GcX34a" aria-expanded="false" aria-haspopup="true">
                    <div class="fd-input-group">
                        <input type="text" class="fd-input fd-input--compact fd-input-group__input" id="" placeholder="Select Fruit">
                        <span class="fd-input-group__addon fd-input-group__addon--button fd-input-group__addon--compact">
                            <button class="fd-input-group__button fd-button--light fd-button--compact sap-icon--value-help"></button>
                        </span>
                    </div>
                </div>
            </div>
            <div class="fd-popover__body fd-popover__body--no-arrow" aria-hidden="true" id="F4GcX34a">
                <ul class="fd-dropdown-list fd-dropdown-list--compact">
                     <li class="fd-multi-input__element" role="option">
                        <label class="fd-dropdown-list__item fd-multi-input__label is-selected" for="a2">
                            <input type="checkbox" class="fd-checkbox fd-multi-input__input fd-checkbox--compact" checked id="a2">
                            <span class="fd-dropdown-list__title">Apple</span>
                            <span class="fd-dropdown-list__secondary">A2</span>
                        </label>
                    </li>
                    <li class="fd-multi-input__element" role="option">
                        <label class="fd-dropdown-list__item fd-multi-input__label" for="b2">
                            <input type="checkbox" class="fd-checkbox fd-multi-input__input fd-checkbox fd-checkbox--compact" id="b2">
                            <span class="fd-dropdown-list__title">Berry</span>
                            <span class="fd-dropdown-list__secondary">B2</span>
                        </label>
                    </li>
                    <li class="fd-multi-input__element" role="option">
                       <label class="fd-dropdown-list__item fd-multi-input__label" for="c2">
                           <input type="checkbox" class="fd-checkbox fd-multi-input__input fd-checkbox--compact" id="c2">
                           <span class="fd-dropdown-list__title">Banana</span>
                           <span class="fd-dropdown-list__secondary">C2</span>
                       </label>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    <div class="fd-multi-input-tags">
        <span class="fd-token" role="button">Apple</span>
        <span class="fd-token" role="button">Berry</span>
        <span class="fd-token" role="button">Banana</span>
    </div>
</div>
{% endcapture %}
{% include display-component.html component=default %}
