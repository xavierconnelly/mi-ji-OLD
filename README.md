# Office Mi-Ji


**Saving images**

1. You need 4 files per image
   a. Blur JPeg
   b. Blur Webp
   c. Clear JPeg
   d. Clear Webp
4. Save at 800px wide
5. Save with 'projectname_01', 'projectname_02', 'projectname_03' etc.
6. Save plan as 'projectname_plan'


**Adding images to Github**
---
1. Save images
2. In Github create a new folder in the 'image' folder
3. Make new file name
4. Upload image



For Desktop
---
        <div class="swiper-slide column COLOUR">
          <div class="carousel">
            <div class="photo">
              <picture class="blur">
                <source type="image/webp" srcset="./images/PROJECTNAME/01_800_Blur.webp">
                <source type="image/jpg" srcset="./images/PROJECTNAME/01_800_Blur.jpg">
                <img src="./images/PROJECTNAME/01_800_Blur.JPG" width="800" height="1200" alt="photo of the PROJECTNAME project">
              </picture>
              <picture class="clear">
                <source type="image/webp" srcset="./images/PROJECTNAME/01_800.webp">
                <source type="image/jpg" srcset="./images/PROJECTNAME/01_800.jpg">
                <img src="https://mi-ji.com.au/images/PROJECTNAME/01_800.JPG" width="800" height="1200" alt="photo of the PROJECTNAME project">
              </picture>
            </div>
            <div class="plan" data-collapsed="true" style="height: 0px">
              <picture>
                <source type="image/svg" srcset="./images/PROJECTNAME/Plan_800.svg">
                <img src="./images/PROJECTNAME/Plan_800.svg" width="800" height="1120" alt="architectural plan of the PROJECTNAME project">
              </picture>
            </div>
          </div>
          <div class="words-box">
            <span class="words">Insert text here
            </span>
          </div>
        </div>
        
With the above code;

1. Replace 'COLOUR' with the selected colour for the project.
  a. Choose from; pink | red | yellow | pistacio | grey | green

2. Replace 'PROJECTNAME' with the folder name for the project 

3. Insert desired text 

4. Repeat for each project image — changing the '01' succeeding the file name to '02', '03' etc

5. Copy the code

6. Open the index.html file in Github

7. Click the edit button in the top right

8. Paste the text in between the existing photo sections in the top (desktop) section of code


For Mobile
---

          <div class="mySlides fade COLOUR">
              <div class="additonal">
                  <picture class="clear photo">
                      <source type="image/webp" srcset="./images/PROJECTNAME/01_800.webp">
                      <source type="image/jpg" srcset="./images/PROJECTNAME/01_800.jpg">
                      <img src="./images/PROJECTNAME/01_800.JPG" alt="photo of the PROJECTNAME project">
                  </picture>
                  <picture class="clear photo" style="padding-bottom: 100px;">
                      <source type="image/svg" srcset="./images/PROJECTNAME/Plan_800.svg">
                      <img src="./images/PROJECTNAME/Plan_800.svg" alt="plam of the PROJECTNAME project">
                  </picture>
              </div>
              <div class="words-box">
                  <p class="words">
                    Insert text here
                  </p>
              </div>
              <a class="prev" onclick="plusSlides(-1)">
                  <img src="https://mi-ji.com.au/assets/prev_COLOUR.svg">
              </a>
              <a class="next" onclick="plusSlides(1)">
                  <img src="https://mi-ji.com.au/assets/next_COLOUR.svg">
              </a>
          </div>
---

With the above code;

1. Replace 'COLOUR' with the selected colour for the project.
  a. Choose from; pink | red | yellow | pistacio | grey | green

2. Replace 'PROJECTNAME' with the folder name for the project 

3. Add extra photos as needed by copying the picture section
  a. change the '01' to '02', '03' etc

                  <picture class="clear photo">
                      <source type="image/webp" srcset="./images/PROJECTNAME/02_800.webp">
                      <source type="image/jpg" srcset="./images/PROJECTNAME/02_800.jpg">
                      <img src="./images/PROJECTNAME/02_800.JPG" alt="photo of the PROJECTNAME project">
                  </picture>

4. Insert desired text 

5. Copy and paste code from the first '<div clas....' down
