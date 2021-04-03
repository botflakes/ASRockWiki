# > ASRock Rack Overview

# Search (test)

<form action="{{ page.url | relative_url }}">
  <div class="tipue_search_left"><img src="{{ "/assets/tipuesearch/search.png" | relative_url }}" class="tipue_search_icon"></div>
  <div class="tipue_search_right"><input type="text" name="q" id="tipue_search_input" pattern=".{3,}" title="At least 3 characters" required></div>
  <div style="clear: both;"></div>
</form>

<div id="tipue_search_content"></div>

<script>
$(document).ready(function() {
  $('#tipue_search_input').tipuesearch();
});
</script>

## Notice
You have a BIOS which isn't listed here? Let us know in a <a style="color:#79bd28" href="https://www.reddit.com/message/compose?to=%2Fr%2FASRock" target="_blank">modmail!</a>  
Dead link? Report it <a style="color:#79bd28" href="https://forms.gle/ApqAN72vS6sxzFnm7" target="_blank">here</a>  

## Warning
<p style="color:#840000;text-align:center">We're not responsible for any damage that may happen to your board! Flashing a new BIOS does always have its risks!</p>

***

- [ASRockRack Beta BIOS](beta_bios_rack_bios)

- [ASRockRack Beta BMCs](beta_bios_rack_bmc)
