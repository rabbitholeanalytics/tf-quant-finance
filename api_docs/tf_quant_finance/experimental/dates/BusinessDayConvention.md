<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf_quant_finance.experimental.dates.BusinessDayConvention" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="FOLLOWING"/>
<meta itemprop="property" content="MODIFIED_FOLLOWING"/>
<meta itemprop="property" content="MODIFIED_PRECEDING"/>
<meta itemprop="property" content="NONE"/>
<meta itemprop="property" content="PRECEDING"/>
</div>

# tf_quant_finance.experimental.dates.BusinessDayConvention

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api" align="left">
</table>

<a target="_blank" href="https://github.com/google/tf-quant-finance/blob/master/tf_quant_finance/experimental/dates/constants.py">View source</a>



Conventions that determine how to roll dates that fall on holidays.

<!-- Placeholder for "Used in" -->

* `NONE`: No adjustment
* `FOLLOWING`: Choose the first business day after the given holiday.
* `MODIFIED_FOLLOWING`: Choose the first business day after the given holiday
unless that day falls in the next calendar month, in which case choose the
first business day before the holiday.
* `PRECEDING`: Choose the first business day before the given holiday.
* `MODIFIED_PRECEDING`: Choose the first business day before the given holiday
unless that day falls in the previous calendar month, in which case choose the
first business day after the holiday.

## Class Variables

* `FOLLOWING` <a id="FOLLOWING"></a>
* `MODIFIED_FOLLOWING` <a id="MODIFIED_FOLLOWING"></a>
* `MODIFIED_PRECEDING` <a id="MODIFIED_PRECEDING"></a>
* `NONE` <a id="NONE"></a>
* `PRECEDING` <a id="PRECEDING"></a>