--- 
layout: feature 
lang: en 
fileName: en

---


<div class="container">
    <div class="row">
         <div class="col col-sm-12 col-md-12 col-lg-12">
         <br>
         <p style="color:yellow;font-size:60px;text-shadow: 3px 8px black"><u>JPG/JPEG/PNG TO WEBP CONVERTER</u></p>
         </div>
    </div>
    <dv class="row">
        <div class="col col-sm-12 col-md-12 col-lg-12" style="border:2px solid black;background:black;color:red;border-radius:100px">
            <br> 
            <input type="file" accept="image/*" id="input" onchange="convert()" style="margin-top:40px;margin-left:100px;font-size:20px">
                <br><br>
            <input type="text" id="width" placeholder="enter the width" style="border:3px solid black;border-radius:25px;height:35px">
            X
            <input type="text" id="height" placeholder="enter the height" style="border:3px solid black;border-radius:25px;height:35px">
            <br>
            <br>
            <button type="button" onclick="resolution()" style="border-radius:25px;border:3px solid" class="btn btn-dark">
            CHANGE RESOLUTION
            </button>
            <br>
            <br>
            <button type="button" class="btn btn-dark" onclick="download()" style="color:red;border-radius:25px">
            CONVERT
            </button><br><br>
            <canvas id="canvas" height="1" width="1" style="border:2px solid black">         
            </canvas>
            <br>
            <span id="but"></span>
            <br>
            <br>
        <div>
    </div>
</div>

{% include pt.html %}