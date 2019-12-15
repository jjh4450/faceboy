> ## FACE BOY
> ### AI's opinion of your face
> made by 목민수, 조준환, 최유현
site link: [https://aiopininonofyourface.netlify.com](https://aiopininonofyourface.netlify.com/)
and you can learn more in bit.ly/faceboy we use [google sites](https://sites.google.com/new) for made this site


### How did you teach AI?

AI training:[https://teachablemachine.withgoogle.com/](https://teachablemachine.withgoogle.com/)
if you have a question about this site thand [click this link](https://teachablemachine.withgoogle.com/faq)


we made image croawling prgram[(dowload exe file)](https://sites.google.com/view/faceboy/%EC%A0%9C%EC%9E%91%EB%B0%A9%EB%B2%95?authuser=1#h.p_Vpm6hnMARFva
) try to teach AI 

AI file in my_model folder

### How is the AI ​​output printed?
you can learn more [in this link](https://github.com/googlecreativelab/teachablemachine-community/tree/master/libraries/image)
we made like this

    async function predict() {
            // predict can take in an image, video or canvas html element
            const prediction = await model.predict(webcam.canvas);

            var classPrediction_Int =
                (prediction[0].probability.toFixed(2) * 100).toFixed(0);
            var classPrediction =
                prediction[0].className;
            var classPrediction_Int1 =
                (prediction[1].probability.toFixed(2) * 100).toFixed(0);
            var classPrediction1 =
                prediction[1].className;
            if (classPrediction == "handsome" && classPrediction_Int > 95) {
                labelContainer.childNodes[0].innerHTML = classPrediction + ' : ' + classPrediction_Int + '%<br>' + classPrediction1 + ' : ' + classPrediction_Int1 + '<br>' + "Result : Very Handsome!!";
            }
            else if (classPrediction == "handsome" && classPrediction_Int > 90 && classPrediction_Int <= 95) {
                labelContainer.childNodes[0].innerHTML = classPrediction + ' : ' + classPrediction_Int + '%<br>' + classPrediction1 + ' : ' + classPrediction_Int1 + '<br>' + "Result : Handsome";
            }
            else if (classPrediction == "handsome" && classPrediction_Int > 85 && classPrediction_Int <= 90) {
                labelContainer.childNodes[0].innerHTML = classPrediction + ' : ' + classPrediction_Int + '%<br>' + classPrediction1 + ' : ' + classPrediction_Int1 + '<br>' + "Result : good";
            }
            else if (classPrediction == "handsome" && classPrediction_Int > 50 && classPrediction_Int <= 85) {
                labelContainer.childNodes[0].innerHTML = classPrediction + ' : ' + classPrediction_Int + '%<br>' + classPrediction1 + ' : ' + classPrediction_Int1 + ' <br>' + "Result : normal";
            }
            else if (classPrediction1 == "ugly" && classPrediction_Int1 >= 95) {
                labelContainer.childNodes[0].innerHTML = classPrediction + ' : ' + classPrediction_Int + '%<br>' + classPrediction1 + ' : ' + classPrediction_Int1 + '<br>' + "Result : It's okay...";
            }
            else if (classPrediction1 == "ugly" && classPrediction_Int1 >= 90 && classPrediction_Int < 90) {
                labelContainer.childNodes[0].innerHTML = classPrediction + ' : ' + classPrediction_Int + '%<br>' + classPrediction1 + ' : ' + classPrediction_Int1 + '<br>' + "Result : ugly";
            }
            else if (classPrediction1 == "ugly" && classPrediction_Int1 >= 85 && classPrediction_Int < 90) {
                labelContainer.childNodes[0].innerHTML = classPrediction + ' : ' + classPrediction_Int + '%<br>' + classPrediction1 + ' : ' + classPrediction_Int1 + '<br>' + "Result : unusual";
            }
            else if (classPrediction1 == "ugly" && classPrediction_Int1 >= 50 && classPrediction_Int < 85) {
                labelContainer.childNodes[0].innerHTML = classPrediction + ' : ' + classPrediction_Int + '%<br>' + classPrediction1 + ' : ' + classPrediction_Int1 + '<br>' + "Result : normal";
            }
            else {
                labelContainer.childNodes[0].innerHTML = "Unknown";
            }
        }
###   Is this artificial intelligence a good judge?
I'm not sure because only 220 people do this AI and many people say "AI said I'am very handsome!!"
but... I never saw it more than normal...

picopass127@gmail.com / bit.ly/faceboy
