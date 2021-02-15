--- 
layout: feature 
lang: en 
fileName: en

---


<div class="container">
    <div class="row">
         <div class="col col-sm-12 col-md-12 col-lg-12">
         <br>
         <p style="color:yellow;font-size:65px;text-shadow: 3px 9px black"><u>WEBP TO JPG/JPEG/PNG CONVERTER</u></p>
         </div>
    </div>
    <dv class="row">
        <div class="col col-sm-12 col-md-12 col-lg-12" style="border:2px solid black;background:black;color:red;border-radius:100px">
            <br> 
            <input type="file" accept="image/*" id="input" onchange="convert()" style="margin-top:40px;margin-left:50px;font-size:20px">
                <br>
                <br>
                PLEASE ENTER THE FORMAT
                <select class="form-select form-select-lg mb-3" aria-label=".form-select-lg example" id="c" style="font-size:17px">
                    <option selected>Open this select menu</option>
                    <option value="jpg">jpg</option>
                    <option value="jpg">jpeg</option>
                    <option value="png" selected>png</option>
                </select>
                <br>
                <br>
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
            </button><br><br><br>
            <canvas id="canvas" width="1" height="1" style="border:2px solid black">         
            </canvas>
            <br>
            <span id="but"></span>
            <br>
            <br>
        <div>
    </div>
</div>

{% include script.html %}