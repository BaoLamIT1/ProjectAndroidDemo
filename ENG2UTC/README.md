Đây là project lớn nhất đầu tiên của tôi. Là 1 app mobile học Tiếng Anh. 
(This is my first biggest project that i've ever made. An English Learning Mobile App)
## IntroActivity
<img src="README_Img/IntroActivity.png" alt="Intro Activity" style="width:33%;">

## Login and SignUp
<p>Layout for Log In and Sign Up. I use Firebase Authentication for storing data and authorization when 
users want to create a new account. Btw, if you already have an account so let's move on ...</p>

<table>
  <tr>
    <td>
      <img src="README_Img/SignUpActivity.png" alt="SignUp Activity" style="width: 200px; height: auto;">  
      <br>
      <p align="center">Sign Up</p>
    </td>
    <td>
      <img src="README_Img/LogInActivity.png" alt="LogIn Activity" style="width: 200px; height: auto;">  
      <br>
      <p align="center">Log In</p>
    </td>
  </tr>
</table>

## HomeFragment 
- So basically my app is for Vietnamese users want to learn English and have a desire to improve 
their English.
- Firstly, i have a Vocabulary Section which is arranged from A1-B2 level based on Cambridge (I still
  develop it to arrange from each subject)
- Secondly, I have grammar section. I divide this GrammarFragment section by level A1-B2.
  Also it contain many other sections that user can choose to learn. Honestly, just a few pictures
that i capture (cuz i'm lazy to create data for this bruhhhh...)
- The Expression and Reading section sill under developing progress
<table>
  <tr>
    <td>
      <img src="README_Img/homeFragment.png" alt="Home Fragment" style="width: 200px; height: auto;">  
      <br>
      <p align="center">Home</p>
    </td>
    <td>
      <img src="README_Img/grammarFragment.png" alt="Grammar Fragment" style="width: 200px; height: auto;">  
      <br>
      <p align="center">Grammar</p>
    </td>
  </tr>
</table>

## Search Word By Using Free Dictionary API
- In this part i use free dictionary api: https://dictionaryapi.dev/
- All the usages is depends on all you use this API
- If you want to utilise this free API you may have to using RecyclerView, Adapter.
- First create a SearchBar (HomeFragment) and a listener which delivers your searched word to 
SearchedWord Activity. In this SearchedWordActivity, you have to create 2 RecyclerView, the first 
one is for displaying the audio and phonetics, and one is for displaying word definitions, part of
speech, examples, ....


<img src="README_Img/searchWordActivity.png" alt="darkModeHome" style="width:30%"> 


## TranslateFragment 
- In this Fragment, I intend to create Language Translator that using Firebase natural language model and some open-source
library and some python code.
- My first goal is create just a simple translator that translate between English and Vietnamese.

<table>
  <tr>
    <td>
      <img src="README_Img/TranslateFragment_1.png" alt="Translate1" style="width: 200px; height: auto;">  
      <br>
      <p align="center">Translate En-Vn</p>
    </td>
    <td>
      <img src="README_Img/TranslateFragment_2.png" alt="Translate2" style="width: 200px; height: auto;">  
      <br>
      <p align="center">Translate Vn-En</p>
    </td>
  </tr>
</table>


## Vocabulary Learning Section 
- In this section you can learn some Vocabulary which is sorted by level based on Cambridge CERF. As 
I still add some vocab in database so i only add A1-B1 vocabulary. 

<table>
  <tr>
    <td><img src="README_Img/vocabularyLevel.png" alt="vocabLevel" width="1440"><br><p align="center">Level</p></td>
    <td><img src="README_Img/vocabA1.png" alt="vocabA1" width="1440"><br><p align="center">A1</p></td>
    <td><img src="README_Img/vocabA2.png" alt="vocabA2" width="1440"><br><p align="center">A2</p></td>
  </tr>
</table>

- Inside each topic, ENG2UTC have bunch of words that include their pronunciation, part of speech, image,
also vietnamese meaning and audio. That all store in firebase storage.

<table>
  <tr>
    <td><img src="README_Img/a1_Zoo.png" alt="a1zoo" width="1440"><br><p align="center">A1_Zoo</p></td>
    <td><img src="README_Img/a1_Emotion.png" alt="a1emote" width="1440"><br><p align="center">A1_Emotions</p></td>
    <td><img src="README_Img/a2_Places.png" alt="a2places" width="1440"><br><p align="center">A2_Places</p></td>
  </tr>
</table>

## Grammar Fragment 
- In this fragment I just add use of 12 English tenses. All of tense are just some images that i copy 
from some source (P/s: ergggh)
<table>
  <tr>
    <td><img src="README_Img/grammar_all_tenses.png"  width="1440"><br><p align="center">All tenses</p></td>
    <td><img src="README_Img/grammar_presentSimple.png" width="1440"><br><p align="center">Present Simple</p></td>
  </tr>
</table>


##  Setting Activity
- Like other app, my app also have some setting configuration. As i've mentioned above,
this app is created for Vietnamese users. So I only add 2 displayed language VN-ENG
- Also there will be a dark theme.
- Both language and change theme in this app, i use SharedPreference in SettingActivity and 
BaseActivity that all others Activity and Fragment are extended with.
<table>
  <tr>
    <td><img src="README_Img/settingActivity.png" alt="Setting Activity" width="1440"></td>
    <td><img src="README_Img/settingDark.png" alt="darkModeHome" width="1440"></td>
    <td><img src="README_Img/homeDark.png" alt="darkModeHome" width="1440"></td>

  </tr>
</table>








