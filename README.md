## Van Vinh's Portfolio

These are some project I wrote in my free time, in purpose of learning Android SDK and keep my skills up to date.

- [OfflineFirst](#offlinefirst)
- [AndroidCanvas](#androidcanvas)
- [BookMyShow](#bookmyshow)

### OfflineFirst

**Inspiration**

It is written to demonstrate how the application can be designed to work offline and properly sync with the server as network becomes available, with minimal distraction to the user experience.
This topic was presented by Yigit Boyar via his The Android Architecture Talk at Android Dev Summit 2015.  
[talk by Yigit Boyar](https://www.youtube.com/watch?v=70WqJxymPr8&t=574s)  
[his source code](https://github.com/yigit/dev-summit-architecture-demo)

In that meantime, Android Architecture was beta and I wanted to try them out. Beside, Kotlin was introduced as Android future language.


**Targets and Challenges**
* Kotlin language
* Kotlin coroutine
* Android Architechture Components:
  * LiveData
  * ViewModel
  * Room
* android-JobScheduler
* MVVM architechture design
* Self-challenge:
  * For listening to local database change mechanism, instead of using Android supported Room-LiveData, I made the alternative by using Android Content Provider and Content Observer for this


**Source Code**  
[git](https://github.com/mrThinBone/OfflineFirst)





### AndroidCanvas

**Inspiration**  
As title, every UI component starts with Canvas, also plenty of awesome UI libraries outside and blogs/articles cover how to Android customview make me wonder if I can do some.


**Components**
* Social Share
  * Inspiration: this was inspired from awesome idea from [uplab#minimal-social-links](https://www.uplabs.com/posts/minimal-social-links) and haven't had anyone make it for Android yet.
* ThreeDots and AnimatedCircle
  * Inspiration: like [Animated arcs](https://raw.githubusercontent.com/florent37/MyLittleCanvas/master/medias/example/sample_arc.gif) and [Animated dots](https://raw.githubusercontent.com/florent37/MyLittleCanvas/master/medias/example/dots_sample.gif) from [MyLittleCanvas](https://github.com/florent37/MyLittleCanvas) but I used primitive Android Canvas
* ...
  * There're some more, either from some other libraries or my idea, but written in Kotlin and purpose of learing Android Canvas


**Source Code**  
[git](https://github.com/mrThinBone/AndroidCanvas)





### BookMyShow

**Inspiration**  
Recently, I started learning Android "again" from this brilliant [Styling Android](https://blog.stylingandroid.com/about/) blog and find an app to make to apply what I've been learning.  
I found this awesome app design and decided to make this app.  
[BookMyShow-App-UI-Redesign](https://www.behance.net/gallery/63143545/BookMyShow-App-UI-Redesign)

**Demo video**  
Here what I've achieved so far.  
[youtube][bookmyshow_youtube]


**SourceCode**  
I'm making this app in purpose of learning, I'm not having intent of publishing this app once I've done as I havn't asked for permisson from the design owner yet.  
Therefore, source code will not be shared in this mean time.

