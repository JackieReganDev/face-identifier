# Using Azure's cognitive services (computer vision and Face api) users can upload a photo and have their emotions analyzed!
  - live version: https://emotion-chex.herokuapp.com/


# Install

`npm install`

---

# Things to add

- Create a config folder with a `.env` file and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - CLOUD_NAME = `your cloudinary cloud name`
  - CLOUD_API_KEY = `your cloudinary api key`
  - CLOUD_API_SECRET = `your cloudinary api secret`
  - MS_COMPUTER_VISION_SUBSCRIPTION_KEY = `your Microsoft Subscription Key`
  - MS_COMPUTER_VISION_ENDPOINT = `your Microsoft Computer Vision Endpoint`
  - MS_FACE_ENDPOINT = `your Microsoft Face Endpoint`
  - MS_FACE_SUB_KEY = `your Microsoft Face Key`

---

# Run

`npm start`

# How to Edit Multipart Form Button

  add class="form-control" to your form, then style it with the following:

    .form-control {
    display: block;
    width: 100%;
    height: 34px;
    padding: 6px 12px;
    font-size: 14px;
    line-height: 1.42857143;
    color:white;
    /* background-color: rgb(214, 20, 231); */
    background-image: none;
    /* border: 1px solid #ccc; */
    border-radius: 2px;
    -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,0.075);
    box-shadow: inset 0 1px 1px rgba(0,0,0,0.075);
    -webkit-transition: border-color ease-in-out .15s, -webkit-box-shadow ease-in-out .15s;
    -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}


::-webkit-file-upload-button {
  color:white;
  background-color: rgb(214, 20, 231);
  font-family: 'Lato', sans-serif;
  text-transform: uppercase;
  border: 0;
  border-radius: 2px;
  font-size: 12px;
  line-height: 32px;
  height: 28px;
  font-weight: bold;
  text-align: center;
  vertical-align: middle;
  cursor: pointer;
  white-space: nowrap;
  padding: 0 12px;
}

/* for poor sods using IE */
::-ms-browse {
color: black;
  background-color: #2196f3;
  font-family: 'Lato', sans-serif;
  text-transform: uppercase;
  border: 0;
  border-radius: 2px;
  font-size: 12px;
  line-height: 32px;
  height: 32px;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  cursor: pointer;
  white-space: nowrap;
  padding: 0 12px;
}
