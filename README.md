# Fishing script for QB

# About
Optimized
Fish anywhere
Random loot pool
3 diffrent skillbars to choose from
Utilizes qb-target,qb-menu,& text ui

# images
<strong>Regular Fish</strong>

![image](https://user-images.githubusercontent.com/103960355/174501546-4f07ca0a-3927-4da8-9e4c-1cbd69e82f64.png)
![image](https://user-images.githubusercontent.com/103960355/174501557-12503482-5353-4b0b-ab42-6627bd6ece25.png)
![image](https://user-images.githubusercontent.com/103960355/174501561-e33a1457-d10a-49e5-b26b-c2e4b082de0c.png)
![image](https://user-images.githubusercontent.com/103960355/174501565-b200625f-749f-44d1-973e-6bef77998dca.png)
![image](https://user-images.githubusercontent.com/103960355/174501573-0c11c570-9846-42b3-8891-25f4c4469579.png)

<strong>Trash items</strong>

![image](https://user-images.githubusercontent.com/103960355/174501628-c2cd8101-e819-4ea2-9b1a-f27998d7e7aa.png)
![image](https://user-images.githubusercontent.com/103960355/174501637-3552503d-8ffd-41d7-90ad-3661fe91e8b1.png)

<strong>Exotic Fish</strong>

![image](https://user-images.githubusercontent.com/103960355/174501650-cceb55d6-4941-464d-9485-c7010596b485.png)
![image](https://user-images.githubusercontent.com/103960355/174501655-a2430259-787c-4ede-98ef-a651a58ba722.png)
![image](https://user-images.githubusercontent.com/103960355/174501657-71f786d4-07c8-4d71-963d-fe30d5e696e7.png)
![image](https://user-images.githubusercontent.com/103960355/174501662-14dfca80-37ab-4983-a92f-9b9830ccfe59.png)

<strong>Gear & items</strong>

![image](https://user-images.githubusercontent.com/103960355/174501677-fd94e7e1-f2e2-45d5-af0c-4e9d677c78c6.png)
![image](https://user-images.githubusercontent.com/103960355/174501685-4e1dce34-87a9-4f9c-8b56-d5d0359560ac.png)
![image](https://user-images.githubusercontent.com/103960355/174501693-15f298ca-ee8b-4af7-8787-3a1c37c48b1d.png)
![image](https://user-images.githubusercontent.com/103960355/174501697-6e3ff2ed-ea38-4f40-a415-a2cd9c13d8ed.png)

<strong>Rewards</strong>

![image](https://user-images.githubusercontent.com/103960355/174501735-fd543f4a-9add-4b51-92bf-67f87d46ee8f.png)
![image](https://user-images.githubusercontent.com/103960355/174501740-1b2be559-7368-4e75-990f-87a68a901236.png)
![image](https://user-images.githubusercontent.com/103960355/174501746-b5c709e0-6c03-4a72-b6a9-3263cc4622b7.png)
![image](https://user-images.githubusercontent.com/103960355/174501748-c8c13609-e842-4407-8e7b-0996c72d1291.png)
![image](https://user-images.githubusercontent.com/103960355/174501752-244fa63f-d607-411a-84f4-901e2bb8f178.png)

# Required
<li>qb-core/shared.lua info</li>

<pre class="notranslate"><code>	-- Regular Fish
	['stingray'] 			     	 = {['name'] = 'stingray', 				    ['label'] = 'Stingray',            		['weight'] = 2500,      ['type'] = 'item',      ['image'] = 'stingray.png',         	['unique'] = true,     ['useable'] = false,     ['shouldClose'] = false,     ['combinable'] = nil,   ['description'] = 'Stingray'},
	['flounder'] 			     	 = {['name'] = 'flounder', 				    ['label'] = 'Flounder',            		['weight'] = 2500,      ['type'] = 'item',      ['image'] = 'flounder.png',         	['unique'] = true,     ['useable'] = false,     ['shouldClose'] = false,     ['combinable'] = nil,   ['description'] = 'Flounder'},
	['codfish'] 			     	 = {['name'] = 'codfish', 				    ['label'] = 'Cod',            			['weight'] = 2500,      ['type'] = 'item',      ['image'] = 'codfish.png',         		['unique'] = true,     ['useable'] = false,     ['shouldClose'] = false,     ['combinable'] = nil,   ['description'] = 'Cod'},
	['mackerel'] 			     	 = {['name'] = 'mackerel', 				    ['label'] = 'Mackerel',            		['weight'] = 2500,      ['type'] = 'item',      ['image'] = 'mackerel.png',         	['unique'] = true,     ['useable'] = false,     ['shouldClose'] = false,     ['combinable'] = nil,   ['description'] = 'Mackerel'},
	['bass'] 			 		 	 = {['name'] = 'bass', 						['label'] = 'Bass',                     ['weight'] = 1250,      ['type'] = 'item',      ['image'] = 'bass.png',                 ['unique'] = true,     ['useable'] = false,     ['shouldClose'] = false,     ['combinable'] = nil,   ['description'] = 'A normal fish Tatses pretty good!'},
	
	-- Trash Items
	['fishingtin'] 			 	 	 = {['name'] = 'fishingtin', 				['label'] = 'Fishing Tin', 				['weight'] = 2500, 		['type'] = 'item', 		['image'] = 'fishingtin.png', 			['unique'] = false,    ['useable'] = false, 	['shouldClose'] = false,	 ['combinable'] = nil,   ['description'] = 'Fishing Tin'},	
	['fishingboot'] 			 	 = {['name'] = 'fishingboot', 				['label'] = 'Fishing Boot', 			['weight'] = 2500, 		['type'] = 'item', 		['image'] = 'fishingboot.png', 			['unique'] = false,    ['useable'] = false, 	['shouldClose'] = false,	 ['combinable'] = nil,   ['description'] = 'Fishing Boot'},	
	
	-- Exotic Fish
	['killerwhale'] 			 	 = {['name'] = 'killerwhale', 				['label'] = 'Whale', 					['weight'] = 15000, 	['type'] = 'item', 		['image'] = 'killerwhale.png', 			['unique'] = true, 	   ['useable'] = false, 	['shouldClose'] = false,	 ['combinable'] = nil,   ['description'] = 'Killer Whale'},	
	['dolphin'] 			     	 = {['name'] = 'dolphin', 					['label'] = 'Dolphin',          		['weight'] = 5000,      ['type'] = 'item',      ['image'] = 'dolphin.png',       		['unique'] = true,     ['useable'] = false,     ['shouldClose'] = false,     ['combinable'] = nil,   ['description'] = 'Dolphin'},
	['sharkhammer'] 			     = {['name'] = 'sharkhammer', 				['label'] = 'Shark',         			['weight'] = 5000,      ['type'] = 'item',      ['image'] = 'sharkhammer.png',       	['unique'] = true,     ['useable'] = false,     ['shouldClose'] = false,     ['combinable'] = nil,   ['description'] = 'Hammerhead Shark'},
	['sharktiger'] 			     	 = {['name'] = 'sharktiger', 				['label'] = 'Shark',          			['weight'] = 5000,      ['type'] = 'item',      ['image'] = 'sharktiger.png',       	['unique'] = true,     ['useable'] = false,     ['shouldClose'] = false,     ['combinable'] = nil,   ['description'] = 'Tigershark'},
	
	-- Gear
	['fishbait'] 			     	 = {['name'] = 'fishbait', 					['label'] = 'Fish Bait', 				['weight'] = 400, 		['type'] = 'item', 		['image'] = 'fishbait.png', 			['unique'] = false,    ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Fishing bait'},
	['fishingrod'] 			 		 = {['name'] = 'fishingrod', 				['label'] = 'Fishing Rod', 				['weight'] = 750, 		['type'] = 'item', 		['image'] = 'fishingrod.png', 			['unique'] = false,    ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A fishing rod for adventures with friends!!'},	
	['anchor'] 			 	 		 = {['name'] = 'anchor', 					['label'] = 'Boat Anchor', 				['weight'] = 2500, 		['type'] = 'item', 		['image'] = 'anchor.png', 				['unique'] = false,    ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Boat Anchor'},	
	['fishicebox'] 			 	 	 = {['name'] = 'fishicebox', 				['label'] = 'Fishing Ice Chest', 		['weight'] = 2500, 		['type'] = 'item', 		['image'] = 'fishicebox.png', 			['unique'] = true,     ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Ice Box to store all of your fish'},	
	
	-- Rewards
	['fishingloot'] 			 	 = {['name'] = 'fishingloot', 				['label'] = 'Metal Box', 				['weight'] = 500, 		['type'] = 'item', 		['image'] = 'fishingloot.png', 			['unique'] = false,    ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Seems to be a corroded from the salt water, Should be easy to open'},	
	['fishinglootbig'] 			 	 = {['name'] = 'fishinglootbig', 			['label'] = 'Treasure Chest', 			['weight'] = 2500, 		['type'] = 'item', 		['image'] = 'fishinglootbig.png', 		['unique'] = false,    ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'The lock seems to be intact, Might need a key'},	
	['fishingkey'] 			 	 	 = {['name'] = 'fishingkey', 			    ['label'] = 'Corroded Key', 			['weight'] = 100, 		['type'] = 'item', 		['image'] = 'fishingkey.png', 		    ['unique'] = false,    ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weathered key that looks usefull'},	
	['fishtacklebox'] 			 	 = {['name'] = 'fishtacklebox', 			['label'] = 'Tackle Box', 				['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'fishtacklebox.png', 		['unique'] = false,    ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Seems to be left over tackle box from another fisherman'},	
	['pearlscard'] 			 	 	 = {['name'] = 'pearlscard', 				['label'] = 'Pearls Seafood', 			['weight'] = 100, 		['type'] = 'item', 		['image'] = 'pearlscard.png', 			['unique'] = false,    ['useable'] = true, 	   ['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A special member of Pearl\'s Seafood Restaurant'},	

</code></pre>

# Optional (if you are not using my qb-inventory)
<li>This code is to display Inventory Tooltip</li>
<li>inside <code>qb-inventory/html/js/app.js</code> look for the <code>function FormatItemInfo</code></li>


<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>	else if (itemData.name == "bass") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "stingray") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "flounder") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "codfish") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "mackerel") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "dolphin") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "sharkhammer") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "sharktiger") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "killerwhale") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;Species: ' + itemData.info.species + '&lt;/p&gt;Weight: ' + itemData.info.lbs + ' lbs&lt;/p&gt;Type: ' + itemData.info.type);
        } else if (itemData.name == "fishicebox") {
            $(".item-info-title").html('&lt;p&gt;' + itemData.label + ' ' + itemData.info.boxid + '&lt;/p&gt;')
            $(".item-info-description").html('&lt;p&gt;&lt;strong&gt;Box Owner: &lt;/strong&gt;&lt;span&gt;' + itemData.info.boxOwner + '&lt;/span&gt;&lt;/p&gt; Ice Box to store all of your fish');
        }
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="	else if (itemData.name == &quot;bass&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;stingray&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;flounder&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;codfish&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;mackerel&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;dolphin&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;sharkhammer&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;sharktiger&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;killerwhale&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + '</p>')
            $(&quot;.item-info-description&quot;).html('<p>Species: ' + itemData.info.species + '</p>Weight: ' + itemData.info.lbs + ' lbs</p>Type: ' + itemData.info.type);
        } else if (itemData.name == &quot;fishicebox&quot;) {
            $(&quot;.item-info-title&quot;).html('<p>' + itemData.label + ' ' + itemData.info.boxid + '</p>')
            $(&quot;.item-info-description&quot;).html('<p><strong>Box Owner: </strong><span>' + itemData.info.boxOwner + '</span></p> Ice Box to store all of your fish');
        }" tabindex="0" role="button" style="display: inherit;">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>

