_Name and surname:_

#Yulia Kuzich
===

_Contacts:_

* e-mail: uljaonoff@gmail.com
* Discord: @yulyakuzich
* tel.: +48 571 943 819
===

_Short information:_
> My goal is to become a cool front-end developer and get a good job. My strengths include responsibility, perseverance, purposefulness and efficiency. At the moment I havn't work experience in the IT sphere, but I really want to get it. Previously I worked as a logistics manager, but I always want to develop and explore new areas. of activity.
===

_Skills:_
* Git
* HTML
* CSS
* JavaScript 
===

  _Education_
* Bachelor degree in Logistics
* Master degree in World Economics
* RSSchool (stage 0)
===

_Code exaple_
```
//switcher
  function imageSwitcher(event) {
    let currentImageURL = viewerImg.getAttribute("src");
  
    if (currentImageURL) {
      let urlArray = Array.prototype.slice
        .call(images)
        .map((imageElement) => imageElement.attributes.src.value);
  
      let currentImageIndex = urlArray.findIndex((el) => el == currentImageURL);
  
      function goRight() {
        if (currentImageIndex + 1 == urlArray.length) {
          viewerImg.setAttribute("src", urlArray[0]);
        } else {
          viewerImg.setAttribute("src", urlArray[currentImageIndex + 1]);
        }
      }
  
      function goLeft() {
        if (currentImageIndex == 0) {
          viewerImg.setAttribute("src", urlArray[urlArray.length - 1]);
        } else {
          viewerImg.setAttribute("src", urlArray[currentImageIndex - 1]);
        }
      }
      if (event.code == "ArrowRight") {
        goRight();
      }
      if (event.code == "ArrowLeft") {
        goLeft();
      }
      if (event.code == "Escape") {
        closeImage();
      }
    }
  }
  document.addEventListener("keydown", imageSwitcher);
  ```
===
_Languiges_

* Russian (native)
* Franch (B1)
* English (B1)
