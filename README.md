# USER GUIDE

## 1. Step 1

- Goto https://www.trackingmore.com/embed_box_float-es.html and generate your track button. This will generate two scripts in the "Get Code" section

<img src="https://raw.githubusercontent.com/hmphu/tracking-more-logo-replacement/master/img/step1.png" width="60%"/>

- Copy the two generated code
- Paste into your website or the place you want to display the tracking button

## 2. Step 2

- Goto https://pasteboard.co/ and upload your logo
- Copy the generated link

<img src="https://raw.githubusercontent.com/hmphu/tracking-more-logo-replacement/master/img/step2.png" width="60%"/>

## 3. Step 3

- Copy the folowing HTML code and paste after the code from Step 1

```HTML
<div id="over-logo" style="max-width: 1000px; height: 48px; position: absolute; background: #fff; z-index: 99999; display: none;">
    <img src="http://via.placeholder.com/150x45" height="45"/>
</div>
<script type="text/javascript" src="https://textuploader.com/1dsg7/raw"></script>
```

- Edit the `src` url in `img` tag with your logo url from Step 2