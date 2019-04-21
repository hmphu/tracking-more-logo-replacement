# USER GUIDE

## 1. Step 1

- Goto https://www.trackingmore.com/embed_box_float-es.html and generate your track button. This will generate two scripts in the "Get Code" section

<img src="https://raw.githubusercontent.com/hmphu/tracking-more-logo-replacement/master/img/step1.png" width="60%"/>

- Copy the two generated code
- Paste into your website or the place you want to display the tracking button

## 2. Step 2

- Goto https://postimages.org/ and upload your logo
- Copy the "Direct Link"

<img src="https://raw.githubusercontent.com/hmphu/tracking-more-logo-replacement/master/img/step2-new.png" width="60%"/>

## 3. Step 3

- Copy the folowing HTML code

```HTML
<div id="over-logo" style="max-width: 1000px; height: 48px; position: absolute; background: #fff; z-index: 99999; display: none;">
    <img src="http://via.placeholder.com/150x45" height="45"/>
</div>
<script type="text/javascript" src="https://textuploader.com/1dsg7/raw"></script>
```

- Edit the `src` url in `img` tag with your logo url from Step 2. Example:

<img src="https://raw.githubusercontent.com/hmphu/tracking-more-logo-replacement/master/img/step3.png" width="60%"/>

- Then paste the edited code after the HTML code in step 1

- Example completed code:

```HTML
<script type="text/javascript" src="//s.trackingmore.com/plugins/v1/buttonCurrent.js"></script>
<div style="width: 100%;margin:0 auto;text-align:center;">
    <form role="form" action="//track.trackingmore.com" method="get" onsubmit="return false">
        <div class="TM_input-group">
            <input type="text" class="TM_my_search_input_style " value="" id="button_tracking_number" placeholder="Número de Seguimiento" name="button_tracking_number" value="" autocomplete="off" maxlength="100" style="border-color: #fb6e50">
            <span class="TM_input-group-btn">
                <button class="TM_my_search_button_style " id="query" type="button" onclick="return doTrack()" style="background-color: #fb6e50">Seguimiento</button>
            </span>
        </div>
        <input type="hidden" name="lang" value="es" />
        <input id="button_express_code" type="hidden" name="lang" value="" />
    </form>
    <div id="TRNum"></div>
 </div>

<div id="over-logo" style="max-width: 1000px; height: 48px; position: absolute; background: #fff; z-index: 99999; display: none;">
    <img src="https://i.postimg.cc/NMHs5WMN/We-Chat-Image-20190404012017.jpg" height="45"/>
</div>
<script type="text/javascript" src="https://textuploader.com/1dsg7/raw"></script>
```
### [See a demo here](https://rawcdn.githack.com/hmphu/tracking-more-logo-replacement/master/demo.html)