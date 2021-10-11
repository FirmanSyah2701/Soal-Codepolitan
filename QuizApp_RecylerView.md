# Membuat Aplikasi Quiz dengan RecyclerView

# Intro

## Intro

1. Darimanakah asalnya pertanyaan?

    a. xml

    **b. json**

    c. bson

    d. database

2. Berapa jumlah recycler view pada bagian pertanyaan dan apa saja fungsinya?

    a. 1, Membuat halaman pertanyaan

    b. 1, Membuat jawaban dinamis

    c. 1, Kalkulasi score
    
    **d. 2, Menampilkan halaman dan jawaban dinamis**

3. Apa maksudnya jawaban dinamis?   

    a. Saat menjawab langsung muncul score

    b. Saat menjawab langsung muncul benar atau salahnya

    **c. Dalam satu pertanyaan dapat membuat beberapa option jawaban**

    d. a dan b benar

# Membuat Quiz App

## Menyiapkan Proyek

4. Berapa jumlah halaman/screen pada quiz app?

    a. 4

    **b. 5**

    c. 6

    d. 7

5. Bahasa apa yang digunakan untuk membuat quiz app ini?

    a. java

    b. javascript

    c. typescript

    **d. kotlin**

6. Dimana directory untuk mengatur color?

    a. res->color.xml

    **b. res->value->color.xml**

    c. res->themes.xml

    d. res->value->themes.xml

7. Apa saja library yang perlu ditambahkan untuk membuat aplikasi quiz app?

    a. anko, sqlite, gson, glide

    b. anko, sqlite, gson

    **c. anko, gson, glide**

    d. sqlite, gson, glide

8. Apa saja package yang perlu dibuat?

    **a. adapter, model, respository, ui**

    b. adapter, model, ui

    c. adapter, model, respository,

    d. adapter, model, respository, main

## Membuat Halaman Splash Screen

9. Cara membuat activity baru pada package splash adalah...

    a. Klik kanan pada package->New->Android Resource File

    b. klik kanan pada package->New->File

    **c. Klik kanan pada package->New->Activity->Empty Activity**

    d. Klik kanan pada package->New->Activity->Android TV Blank Activity

10. Pada OS windows saat source code R pada setContentView berwarna merah solusinya adalah...

    **a. alt + enter, klik import**

    b. alt + enter, klik Create object R

    c. alt + enter, klik Create class R

    d. alt + enter, klik Create Interface R

11. Dimana paste assets gambar?

    **a. res**

    b. java

    c. res->layout

    d. res->value

12. Source code pada xml untuk membuat gambar berada diposisi tengah adalah...

    a. android:align="center"

    b. android:alignment="center"

    **c. android:layout_centerInParent="true"**

    d. android:layout_centerInParent="false"

13. Komponen untuk menampilkan gambar adalah?
    
    a. TextView

    b. EditText
    
    c. Image

    **d. ImageView**

14. Cara membuat handler delay 12 detik pada kotlin adalah...

    a. Hanlder(Looper.getMainLooper()).postDelayed({}, 12)

    b. Hanlder(Looper.getMainLooper()).postDelayed({}, 120)

    **c. Hanlder(Looper.getMainLooper()).postDelayed({}, 1200)**

    d. Hanlder(Looper.getMainLooper()).postDelayed({}, 12000)

15. Apa yang dipilih saat mengetikkan startActivity agar yang digunakan adalah dari library anko?

    a. startActivity(Intent: Intent)

    b. startActivity(Intent: Intent, option)

    **c. startActivity(vararg params)**

    d. a dan b benar

## Membuat Halaman Home

16. Syntax untuk mengatur ukuran font/text adalah...

    a. android:textSize="14dp"

    **b. android:textSize="14sp"**

    c. android:fontSize="14dp"

    d. android:fontSize="14dp"

17. fungsi dari ``android:lineSpacingExtra`` adalah...

    a. Menambahkan space/jarak pada setiap spasi

    b. Menambahkan space/jarak pada setiap baris

    **c. Menambahkan space/jarak pada setiap spasi baris**

    d. Menambahkan space/jarak pada setiap huruf

18. Cara menambahkan custom background adalah...

    **a. klik kanan pada drawable -> Pilih Drawable Resource File -> Ketik pada file name nama file nya -> klik OK**

    b. klik kanan pada drawable -> Pilih New File -> Ketik pada file name nama file nya -> klik OK

    c. klik kanan pada res -> Pilih Drawable Resource File -> Ketik pada file name nama file nya -> klik OK

    d. klik kanan pada res -> Pilih New File -> Ketik pada file name nama file nya -> klik OK

## Membuat Halaman Prepare Activity

19. Syntax untuk menggunakan view binding pada PrepareActiviy adalah...

    a. 
    ```java
        private lateinit var prepareBinding : ActivityBinding
        ...
        prepareBinding = ActivityBinding.inflate(layoutInflatter)
        setContentView(prepareBinding.root)
    ```

    **b.
    ```java
        private lateinit var prepareBinding : ActivityPrepareBinding
        ...
        prepareBinding = ActivityPrepareBinding.inflate(layoutInflatter)
        setContentView(prepareBinding.root)
    ```
    **

    c.
    ```java
        private lateinit var prepareBinding : ActivityBinding
        ...
        prepareBinding = ActivityBinding.inflate(layoutInflatter)
        setContentView(prepareBinding)
    ```

    d.
    ```java
        private lateinit var prepareBinding : ActivityPrepareBinding
        ...
        prepareBinding = ActivityPrepareBinding.inflate(layoutInflatter)
        setContentView(prepareBinding)
    ```

20. Komponen untuk menginputkan nickname adalah?
    
    a. TextView

    **b. EditText**
    
    c. InputText

    d. FieldText

21. Syntax untuk membuat validasi agar nickname harus diisi terlebih dahulu sebelum klik tombol/button start adalah...

    a. 
    ```java
    private fun onclick() {
        prepareBinding.btnStart.setOnclickListener {
            val nickname = prepareBinding.etNickname.text.toString()
            if(checkValidation(nickname)) {

            }
        }
    }

    private fun checkValidation(nickname: String): Boolean {
        return if(nickname){
            prepareBinding.etNickname.error = getString(R.string.please_field_your_nickname)
            false
        }else {
            true
        }
    }
    ```

    b. 
    ```java
    private fun onclick() {
        prepareBinding.btnStart.setOnclickListener {
            val nickname = prepareBinding.etNickname.text.toString()
            if(checkValidation(nickname)) {

            }
        }
    }

    private fun checkValidation(nickname: String): Boolean {
        return if(nickname != null){
            prepareBinding.etNickname.text = getString(R.string.please_field_your_nickname)
            false
        }else {
            true
        }
    }
    ```

    **c. 
    ```java
    private fun onclick() {
        prepareBinding.btnStart.setOnclickListener {
            val nickname = prepareBinding.etNickname.text.toString()
            if(checkValidation(nickname)) {

            }
        }
    }

    private fun checkValidation(nickname: String): Boolean {
        return if(nickname.isEmpty()){
            prepareBinding.etNickname.error = getString(R.string.please_field_your_nickname)
            false
        }else {
            true
        }
    }
    ```
    **

    d. 
    ```java
    private fun onclick() {
        prepareBinding.btnStart.setOnclickListener {
            val nickname = prepareBinding.etNickname.text.toString()
            if(checkValidation(nickname)) {

            }
        }
    }

    private fun checkValidation(nickname: String): Boolean {
        return if(nickname.isEmpty()){
            prepareBinding.etNickname.text = getString(R.string.please_field_your_nickname)
            true
        }else {
            false
        }
    }
    ```

## Membuat Halaman ContentActivity - 1

22. Cara menambahkan icon close yaitu

    **a. klik kanan drawable -> pilih New -> pilih Vector Asset -> ketik close pada kolom cari -> Pilih icon close -> Klik Ok**

    b. klik kanan drawable -> pilih New -> pilih Image Asset -> ketik close pada kolom cari -> Pilih icon close -> Klik Ok

    c. klik kanan res -> pilih New -> pilih UIComponent -> ketik close pada kolom cari -> Pilih icon close -> Klik Ok

    d. klik kanan res -> pilih New -> pilih Widget -> ketik close pada kolom cari -> Pilih icon close -> Klik Ok 

23. Agar pada icon tidak terdapat warna backgorund

    a. app:background="@android:color/transparent"

    b. android:background="@android:color/transparent"

    c. android:backgroundTint="@android:color/transparent"

    **d. b dan c benar**

24. Source code untuk membuat progress bar dengan datar/horizontal adalah...

    a.
    ```xml 
    <ProgressBar 
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
    ```

    b.
    ```xml 
    <ProgressBar 
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        style="@style/Widget.compat.ProgressBar.Vertical"/>
    ```

    **c.
    ```xml 
    <ProgressBar 
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        style="@style/Widget.compat.ProgressBar.Horizontal"/>
    ```
    **

    d.
    ```xml 
    <ProgressBar 
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        style="@style/Widget.compat.ProgressBar"/>
    ```

## Membuat Halaman ContentActivity - 2

25. Komponen untuk membuat tombol/button circular adalah
    
    a. <Button>

    b. <ImageButton>

    c. <FlatButton>

    **d. <com.google.android.material.FloatingActionbutton.FloatingActionButton>**

26. Komponen untuk mengatur radius pada custom background adalah...

    a. solid

    b. shape

    **c. corners**

    d. ripple

27. Source code untuk membuat FloatingActionButton prev dengan icon anak panah kiri adalah...

    **a.
    ```xml
    <com.google.android.material.FloatingActionbutton.FloatingActionButton
        android:id="@+id/btn_prev"
        android:width="wrap_content"
        android:height="wrap_content"
        android:color="@color/white"
        android:src="@drawable/ic_baseline_keyboard_arrow_left_24"
        app:layout_constraintBottomToBottom="parent"
        app:layout_constraintStartToStart="parent"/>
    ```
    **

    b.
    ```xml
    <com.google.android.material.FloatingActionbutton.FloatingActionButton
        android:id="@+id/btn_prev"
        android:width="wrap_content"
        android:height="wrap_content"
        android:src="@drawable/ic_baseline_keyboard_arrow_right_24"
        app:layout_constraintBottomToBottom="parent"
        app:layout_constraintEndToEnd="parent"/>
    ```

    c.
    ```xml
    <com.google.android.material.FloatingActionbutton.FloatingActionButton
        android:id="@+id/btn_prev"
        android:width="wrap_content"
        android:height="wrap_content"
        android:src="@drawable/ic_baseline_keyboard_arrow_left_24"
        app:layout_constraintBottomToBottom="parent"
        app:layout_constraintEndToEnd="parent"/>
    ```

    d.
    ```xml
    <com.google.android.material.FloatingActionbutton.FloatingActionButton
        android:id="@+id/btn_prev"
        android:width="wrap_content"
        android:height="wrap_content"
        android:src="@drawable/ic_baseline_keyboard_arrow_right_24"
        app:layout_constraintBottomToBottom="parent"
        app:layout_constraintStartToStart="parent"/>
    ```

    

## Membuat Item Content

28. Syntax yang benar untuk membuat halaman dapat di scroll keatas dan kebawah adalah...

    a. <android.core.widget.ScrollView>

    **b. <android.core.widget.NestedScrollView>**

    c. <NestedScrollView>

    d. a dan c benar

29. Source code untuk membuat LinearLayout yang benar adalah

    a. 
    ```xml
    <LinearLayout
        android:width="match_parent"
        android:height="wrap_content"    
    >
    </LinearLayou>
    ```

    b. 
    ```xml
    <LinearLayout
        android:width="match_parent"
        android:height="wrap_content"
        android:orientation="vertical"    
    >
    </LinearLayou>
    ```

    c. 
    ```xml
    <LinearLayout
        android:width="match_parent"
        android:height="wrap_content"
        android:orientation="horizontal"    
    >
    </LinearLayou>
    ```

    **d. b dan c benar**

30. Source code untuk melihat preview text adalah...

    **a. tools:text="Lorem ipsum dolor sit amet"**

    b. app:text="Lorem ipsum dolor sit amet"

    c. style:text="Lorem ipsum dolor sit amet"

    d. android:text="Lorem ipsum dolor sit amet"

## Membuat Item Answer - 1

31. Syntax untuk membuat text menjadi huruf besar semua ialah

    **a. android:textAllCaps="true"**

    b. android:textAllCaps="false"

    c. android:textStyle="AllCaps"

    d. a dan c benar

32. Source code untuk membuat custom background stroke ialah

    a.
    ```xml
        <shape xmlns:android="http://schemas.android.com/apk/res/android"
            android:shape="rectangle">

            <stroke android:radius="12dp"/>
            <corners android:color="@color/colorPrimary"/>

        </shape>
    ```

    b.
    ```xml
        <shape xmlns:android="http://schemas.android.com/apk/res/android"
            android:shape="rectangle">

            <stroke android:radius="12dp"/>
            <corners android:color="@color/colorPrimary" android:width="1dp"/>

        </shape>
    ```

    **c.
    ```xml
        <shape xmlns:android="http://schemas.android.com/apk/res/android"
            android:shape="rectangle">

            <stroke android:color="@color/colorPrimary" android:width="1dp"/>
            <corners android:radius="12dp"/>

        </shape>
    ```
    **

    d.
    ```xml
        <shape xmlns:android="http://schemas.android.com/apk/res/android"
            android:shape="rectangle">

            <solid android:color="@color/colorPrimary" android:width="1dp"/>
            <corners android:radius="12dp"/>

        </shape>
    ```

33. Syntax untuk membuat text tebal ialah

    **a. android:textStyle="bold"**

    b. android:textStyle="italic"

    c. android:textStyle="underline"

    d. android:textStyle="normal"

## Membuat Item Answer - 2

34. Source code yang benar untuk mengubah warna icon pada ImageView ialah...

    a. android:tint="@color/colorPrimary"

    **b. app:tint="@color/colorPrimary"**

    c. android:backgroundTint="@color/colorPrimary"

    d. app:backgroundTint="@color/colorPrimary"

35. Agar ImageView icon panorama fish eye berada di belakang maka perlu menambahkan syntax...

    **a. app:layout_constraintEnd_toEndOf="parent"**

    b. app:layout_constraintTop_toTopOf="parent"

    c. app:layout_constraintBottom_toBottomOf="parent"

    d. app:layout_constraintStart_toStartOf="parent"

36. Source code untuk melihat preview design yang dibuat adalah...

    a. tools:layoutManager="android.recyclerview.widget.LinearLayout"

    **b. tools:listItem="@layout/item_content"**

    c. tools:layoutManager="@layout/item_content"

    d. tools:listItem="android.recyclerview.widget.LinearLayout"

## Membuat Halaman Score Activity

37. Agar ImageView dapat sesuai dengan ukuran aslinya maka perlu menambahkan syntax...

    **a. android:adjustViewBonds="true"**

    b. android:adjustViewBonds="false"

    c. app:adjustViewBonds="true"

    d. app:adjustViewBonds="true"

38. Source code untuk membuat lebar menambah secara otomatis saat text/angka nya banyak tetapi ukuran awal nya adalah 16dp...

    a. 
    ```xml
    <TextView 
        android:width="match_parent"
        android:height="wrap_content"
        android:minWidth="16dp"
    />
    ```

    b. 
    ```xml
    <TextView 
        android:width="match_parent"
        android:height="match_parent"
        android:minHeight="16dp"
    />
    ```

    c. 
    ```xml
    <TextView 
        android:width="wrap_content"
        android:height="match_parent"
        android:minWidth="16dp"
    />
    ```

    **d. 
    ```xml
    <TextView 
        android:width="wrap_content"
        android:height="wrap_content"
        android:minWidth="16dp"
    />
    ```
    **

39. Pada Button untuk menggubah warna pada icon maka perlu menambahkan syntax...

    a. android:textColor="@color/white"

    b. android:background="@color/white"

    **c. android:drawableTint="@color/white"**

    d. android:drawableEnd="@color/white"

## Menambahkan Data Kuis

40. File json sebaiknya diletakkan pada...

    **a. assets folder**

    b. package main folder

    c. res folder

    d. drawable folder

41. Source code untuk mendapatkan data dari json yang benar adalah...

    a.
    ```java
        fun getDataContents(context Context?): List<Content>?{
            val json: String?
            try{
                val inputStream = context?.assets?.open("json/contents.json")
                json = inputStream?.bufferedReader().use{ it.ReadText() }
            }catch(e: IOException){
                return null
            }
        }
    ```

    b.
    ```java
        fun getDataContents(context Context?): List<Content>?{
            val json: String?
            try{
                val inputStream = context?.assets?.open("json/contents.json")
                json = inputStream?.bufferedReader().use{ it.ReadText() }
            }catch(e: IOException){
                
                val contents = Gson().fromJson(json, Contents::Class.java)
                return contents.contents
            }
        }
    ```
    
    **c.
    ```java
        fun getDataContents(context Context?): List<Content>?{
            val json: String?
            try{
                val inputStream = context?.assets?.open("json/contents.json")
                json = inputStream?.bufferedReader().use{ it.ReadText() }
            }catch(e: IOException){
                return null
            }

            val contents = Gson().fromJson(json, Contents::Class.java)
            return contents.contents
        }
    ```
    **

    d.
    ```java
        fun getDataContents(context Context?): List<Content>?{
            val json: String?
            try{
                val inputStream = context?.assets?.open("json/contents.json")
                json = inputStream?.bufferedReader().use{ it.ReadText() }
            }catch(e: IOException){
                val contents = Gson().fromJson(json, Contents::Class.java)
                return contents.contents
            }
            
            return null
        }
    ```

42. Source code untuk mencek data sudah ada atau belum ialah...
    
    **a. 
    ```java
        val contents = Repository.getDataContents(this)
        Log.d("MainActivity", "onCreate: ${contents?.size}")
        Log.d("MainActivity", "onCreate: ${contents?.get(0)?.body}")
    ```
    **

    b. 
    ```java
        val contents = Repository.getDataContents(this)
        print("MainActivity", "onCreate: ${contents?.size}")
        print("MainActivity", "onCreate: ${contents?.get(0)?.body}")
    ```

    c. 
    ```java
        val contents = Repository.getDataContents(this)
        toas("MainActivity", "onCreate: ${contents?.size}")
        toas("MainActivity", "onCreate: ${contents?.get(0)?.body}")
    ```

    d. 
    ```java
        val contents = Repository.getDataContents(this)
        log("MainActivity", "onCreate: ${contents?.size}")
        log("MainActivity", "onCreate: ${contents?.get(0)?.body}")
    ```

## Membuat Content Adapter

43. Fungsi dari adapter adalah

    a. mendapatkan data

    b. mengumpulkan data

    **c. menampilkan data**

    d. membuat data

44. Source code untuk memasukan data/set data pada content adapter yang benar adalah...

    a. 
    ```java
        fun setData(content: MutableList<Content>){
            this.contents = contents
        }
    ```

    b. 
    ```java
        fun setData(content: List<Content>){
            this.contents = contents
        }
    ```

    **c. 
    ```java
        fun setData(content: MutableList<Content>){
            this.contents = contents
            notifyDataSetChanged()
        }
    ```
    **

    d. 
    ```java
        fun setData(content: List<Content>){
            this.contents = contents
            notifyDataSetChanged()
        }
    ```

45. Fungsi dari notifyDataSetChanged() adalah...

    a. untuk memberitahu adapter ada data yang masuk

    b. untuk memberitahu adapter ada data yang berubah

    c. untuk memberitahu adapter ada data yang kosong

    **d. a dan b benar**

## Membuat Answer Adapter

46. Source code untuk membuat jika opsi jawabannya active/true maka imageView nya circle yang checklis kalau false maka imageViewnya tetap panorama_fish_eyes

    a.
    ```java 
    fun bindItem(answer: Answer) {
        itemAnswerBinding.tvOption.text = answer.option
        itemAnswerBinding.tvAnswer.text = answer.answer

        if(answer.isClick??){
            activeCheckAnswer()
        }else{
            inActiveCheckAnswer()
        }
    }

    private fun inActiveCheckAnswer() {
        itemAnswerBinding.ivCheckAnswer.setImageResource(R.drawable.ic_baseline_check_circle_outline_24)
    }

    private fun activeCheckAnswer() {
        itemAnswerBinding.ivCheckAnswer.setImageResource(R.drawable.ic_baseline_panorama_fish_eye_24)
    }
    ```

    b.
    ```java 
    fun bindItem(answer: Answer) {
        itemAnswerBinding.tvOption.text = answer.option
        itemAnswerBinding.tvAnswer.text = answer.answer

        if(answer.isClick?){
            activeCheckAnswer()
        }else{
            inActiveCheckAnswer()
        }
    }

    private fun inActiveCheckAnswer() {
        itemAnswerBinding.ivCheckAnswer.setImageResource(R.drawable.ic_baseline_panorama_fish_eye_24)
    }

    private fun activeCheckAnswer() {
        itemAnswerBinding.ivCheckAnswer.setImageResource(R.drawable.ic_baseline_check_circle_outline_24)
    }
    ```

    c.
    ```java 
    fun bindItem(answer: Answer) {
        itemAnswerBinding.tvOption.text = answer.option
        itemAnswerBinding.tvAnswer.text = answer.answer

        if(answer.isClick!){
            activeCheckAnswer()
        }else{
            inActiveCheckAnswer()
        }
    }

    private fun inActiveCheckAnswer() {
        itemAnswerBinding.ivCheckAnswer.setImageResource(R.drawable.ic_baseline_check_circle_outline_24)
    }

    private fun activeCheckAnswer() {
        itemAnswerBinding.ivCheckAnswer.setImageResource(R.drawable.ic_baseline_panorama_fish_eye_24)
    }
    ```

    d.
    ```java 
    fun bindItem(answer: Answer) {
        itemAnswerBinding.tvOption.text = answer.option
        itemAnswerBinding.tvAnswer.text = answer.answer

        if(answer.isClick!!){
            activeCheckAnswer()
        }else{
            inActiveCheckAnswer()
        }
    }

    private fun inActiveCheckAnswer() {
        itemAnswerBinding.ivCheckAnswer.setImageResource(R.drawable.ic_baseline_panorama_fish_eye_24)
    }

    private fun activeCheckAnswer() {
        itemAnswerBinding.ivCheckAnswer.setImageResource(R.drawable.ic_baseline_check_circle_outline_24)
    }
    ```

47. Source code untuk membuat opsi atau pilihan hanya boleh satu yang aktif dan yang lainnya akan bernilai false ialah...

    a.
    ```java
        itemView.setOnClickListener {
            for (i in 0 until answers.size) {
                answers[i].isClick = i == adapterPosition
            }
        }
    ```

    b.
    ```java
        itemView.setOnClickListener {
            for (i in 0 until answers.size) {
                answers[i].isClick = i == adapterPosition
            }
            notifyDataSetChanged()
        }
    ```

    c.
    ```java
        itemView.setOnClickListener {
            for (i in 0 until answers.size) {
                if(i == adapterPosition){
                    answer[i].isClick = true
                }else{
                    answer[i].isClick = false
                }
            }
            notifyDataSetChanged()
        }
    ```

    **d. b dan c benar**

48. Source code untuk menambahkan AnswerAdapter pada ContentAdapter adalah...

    **a. 
    ```java
        val answerAdapter = AnswerAdapter()
        if(content.answers != null) {
            answerAdapter.setData(content.answers as MutableList<Answer>)

            itemContentBinding.rvAnswerQuiz.adapter = answerAdapter
        }
    ```
    **

    b. 
    ```java
        val answerAdapter = AnswerAdapter(contents)
        if(content.answers != null) {
            answerAdapter.setData(content.answers as MutableList<Answer>)

            itemContentBinding.rvAnswerQuiz.adapter = answerAdapter
        }
    ```

    c. 
    ```java
        val answerAdapter = AnswerAdapter(this)
        if(content.answers != null) {
            answerAdapter.setData(content.answers as MutableList<Answer>)

            itemContentBinding.rvAnswerQuiz.adapter = answerAdapter
        }
    ```
    
    d. 
    ```java
        val answerAdapter = AnswerAdapter(contents)
        if(content.answers == null) {
            answerAdapter.setData(content.answers as MutableList<Answer>)

            itemContentBinding.rvAnswerQuiz.adapter = answerAdapter
        }
    ```

## Menampilkan Data Kuis

49. Source code untuk menampilkan data pada ContentActivity adalah...

    a.
    ```java
    //Show Data
    showDataContents(contents)

    private fun showDataContents(contents: List<Content>?) {
        layoutManager = LinearLayoutManager(this, LinearLayoutManager.HORIZONTAL, false)
        val snapHelper = PagerSnapHelper()

        if(contents == null) {
            contentAdapter.setData(contents as MutableList<Content>)
        }

        snapHelper.attachToRecyclerView(contentBinding.rvContent)
        contentBinding.rvContent.layoutManager = layoutManager
        contentBinding.rvContent.adapter = contentAdapter
    }
    ```

    **b.
    ```java
    //Show Data
    showDataContents(contents)

    private fun showDataContents(contents: List<Content>?) {
        layoutManager = LinearLayoutManager(this, LinearLayoutManager.HORIZONTAL, false)
        val snapHelper = PagerSnapHelper()

        if(contents != null) {
            contentAdapter.setData(contents as MutableList<Content>)
        }

        snapHelper.attachToRecyclerView(contentBinding.rvContent)
        contentBinding.rvContent.layoutManager = layoutManager
        contentBinding.rvContent.adapter = contentAdapter
    }
    ```
    **

    c.
    ```java
    //Show Data
    showDataContents(contents)

    private fun showDataContents(contents:  MutableList<Content>?) {
        layoutManager = LinearLayoutManager(this, LinearLayoutManager.HORIZONTAL, false)
        val snapHelper = PagerSnapHelper()

        if(contents == null) {
            contentAdapter.setData(contents as List<Content>)
        }

        snapHelper.attachToRecyclerView(contentBinding.rvContent)
        contentBinding.rvContent.layoutManager = layoutManager
        contentBinding.rvContent.adapter = contentAdapter
    }
    ```

    d.
    ```java
    //Show Data
    showDataContents(contents)

    private fun showDataContents(contents:  MutableList<Content>?) {
        layoutManager = LinearLayoutManager(this, LinearLayoutManager.HORIZONTAL, false)
        val snapHelper = PagerSnapHelper()

        if(contents != null) {
            contentAdapter.setData(contents as leList<Content>)
        }

        snapHelper.attachToRecyclerView(contentBinding.rvContent)
        contentBinding.rvContent.layoutManager = layoutManager
        contentBinding.rvContent.adapter = contentAdapter
    }
    ```

50. Source code agar SplashActivity dapat dijalankan pertama kali adalah...

    a. 
    ```xml
        <activity
            android:name=".ui.splash.SplashActivity"
            android:exported="true"/>
    ```

    b. 
    ```xml
        <activity
            android:name=".ui.splash.SplashActivity"
            android:exported="true">
        </activity>
    ```

    c. 
    ```xml
        <activity
            android:name=".ui.splash.SplashActivity"
            android:exported="true" />
        <intent-filter>
            <action android:name="android.intent.action.MAIN" />

            <category android:name="android.intent.category.LAUNCHER" />
        </intent-filter>
    ```

    **d. 
    ```xml
        <activity
            android:name=".ui.splash.SplashActivity"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    ```
    **

51. Pada activity content sebaiknya recycelerview content dibungkus dengan...

    a. RecyclerView

    b. LinearLayout

    **c. NestedScrollView**

    d. ConstraintLayout

## Menyimpan Data di SavedInstance dan Menampilkan Index Halaman

52. ```java
    companion object(){
        const val EXTRA_NICKNAME = "extra_nickname"
        const val EXTRA_CONTENTS = "extra_contents"
    }
    ```
    Kedua variable tersebut berfungsi untuk...

    a. menambahkan bundle

    b. mengaktifkan onSavedInstance sehingga data-data yang sudah diklik sebelumnya maka akan tersimpan

    c. menampung data abstrak

    **d. a dan b benar**

53. Souce code untuk mendapatkan data nickname dan content ialah...

    a.
    ```java
        //Get Data
        if(intent == null) {
            nickname = intent.getStringExtra(EXTRA_NICKNAME)
        }

        if(savedInstanceState != null){

            //Get Data From Repository
            val contents = Repository.getDataContents(this)
            //Show Data
            showDataContents(contents)
        }else {
            nickname = savedInstanceState.getString(EXTRA_NICKNAME)
            val contents = savedInstanceState.getParcelableArrayList<Content>(EXTRA_CONTENTS)
            showDataContents(contents)
        }
    ```

    **b.
    ```java
        //Get Data
        if(intent != null) {
            nickname = intent.getStringExtra(EXTRA_NICKNAME)
        }

        if(savedInstanceState != null){
            nickname = savedInstanceState.getString(EXTRA_NICKNAME)
            val contents = savedInstanceState.getParcelableArrayList<Content>(EXTRA_CONTENTS)
            showDataContents(contents)
        }else {
            //Get Data From Repository
            val contents = Repository.getDataContents(this)
            //Show Data
            showDataContents(contents)
        }
    ```
    **

    c.
    ```java
        //Get Data
        if(intent == null) {
            nickname = intent.getStringExtra(EXTRA_NICKNAME)
        }

        if(savedInstanceState != null){
            nickname = savedInstanceState.getString(EXTRA_NICKNAME)
            val contents = savedInstanceState.getParcelableArrayList<Content>(EXTRA_CONTENTS)
            showDataContents(contents)
        }else {
            //Get Data From Repository
            val contents = Repository.getDataContents(this)
            //Show Data
            showDataContents(contents)
        }
    ```

    d.
    ```java
        //Get Data
        if(intent != null) {
            nickname = intent.getStringExtra(EXTRA_NICKNAME)
        }

        if(savedInstanceState != null){
            //Get Data From Repository
            val contents = Repository.getDataContents(this)
            //Show Data
            showDataContents(contents)
        }else {
            nickname = savedInstanceState.getString(EXTRA_NICKNAME)
            val contents = savedInstanceState.getParcelableArrayList<Content>(EXTRA_CONTENTS)
            showDataContents(contents)
        }
    ```

54. Source code untuk mengaktifkan data index pada activity content ialah...

    a.
    ```java
        dataSize = layoutManager.itemCount
        contentBinding.pbContent.max = dataSize

        //First Show Index
        var index = "${currentPosition} / $dataSize"
        contentBinding.tvIndexContent.text = index

        contentBinding.rvContent.addOnScrollListener(object : RecyclerView.OnScrollListener(){
            override fun onScrolled(recyclerView: RecyclerView, dx: Int, dy: Int) {
                super.onScrolled(recyclerView, dx, dy)
                currentPosition = layoutManager.findFirstVisibleItemPosition()
                index = "${currentPosition} / $dataSize"
                contentBinding.tvIndexContent.text = index
                contentBinding.pbContent.progress = currentPosition
            }
        })
    ```

    b.
    ```java
        dataSize = layoutManager.itemCount
        contentBinding.pbContent.max = dataSize + 1

        //First Show Index
        var index = "${currentPosition - 1} / $dataSize"
        contentBinding.tvIndexContent.text = index

        contentBinding.rvContent.addOnScrollListener(object : RecyclerView.OnScrollListener(){
            override fun onScrolled(recyclerView: RecyclerView, dx: Int, dy: Int) {
                super.onScrolled(recyclerView, dx, dy)
                currentPosition = layoutManager.findFirstVisibleItemPosition()
                index = "${currentPosition - 1} / $dataSize"
                contentBinding.tvIndexContent.text = index
                contentBinding.pbContent.progress = currentPosition
            }
        })
    ```

    **c.
    ```java
       dataSize = layoutManager.itemCount
        contentBinding.pbContent.max = dataSize - 1

        //First Show Index
        var index = "${currentPosition + 1} / $dataSize"
        contentBinding.tvIndexContent.text = index

        contentBinding.rvContent.addOnScrollListener(object : RecyclerView.OnScrollListener(){
            override fun onScrolled(recyclerView: RecyclerView, dx: Int, dy: Int) {
                super.onScrolled(recyclerView, dx, dy)
                currentPosition = layoutManager.findFirstVisibleItemPosition()
                index = "${currentPosition + 1} / $dataSize"
                contentBinding.tvIndexContent.text = index
                contentBinding.pbContent.progress = currentPosition
            }
        })
    ```
    **

    d.
    ```java
        dataSize = layoutManager.itemCount
        contentBinding.pbContent.max = dataSize

        //First Show Index
        var index = "${currentPosition + 1} / $dataSize"
        contentBinding.tvIndexContent.text = index

        contentBinding.rvContent.addOnScrollListener(object : RecyclerView.OnScrollListener(){
            override fun onScrolled(recyclerView: RecyclerView, dx: Int, dy: Int) {
                super.onScrolled(recyclerView, dx, dy)
                currentPosition = layoutManager.findFirstVisibleItemPosition()
                index = "${currentPosition + 1} / $dataSize"
                contentBinding.tvIndexContent.text = index
                contentBinding.pbContent.progress = currentPosition
            }
        })
    ```

## Mengaktifkan Tombol di Halaman dan Menghitung Jumlah Score Kuis

55. Komponen untuk memunculkan pesan adalah

    a. Alert

    b. Dialog

    **c. AlertDialog**

    d. DialogAlert

56. Source code untuk menghitung total score ialah...

    a.
    ```java
        val contents = contentAdapter.getResults()
        val totalQuiz = contents.size
        var totalCorrectAnswer = 0

        for (content in contents) {
            for (answer in content.answers!!) {
                if (answer.isClick == true && answer.correctAnswer == true) {
                    totalCorrectAnswer = totalCorrectAnswer + 1
                }
            }
        }

        val totalScore = totalCorrectAnswer / 100 * totalQuiz

        startActivity<ScoreActivity>(
            ScoreActivity.EXTRA_NICKNAME to nickname,
            ScoreActivity.EXTRA_SCORE to totalScore.toInt()
        )
    ```

    b.
    ```java
        val contents = contentAdapter.getResults()
        val totalQuiz = contents.size
        var totalCorrectAnswer = 0

        for (content in contents) {
            for (answer in content.answers!!) {
                if (answer.isClick == true && answer.correctAnswer == true) {
                    totalCorrectAnswer += 1
                }
            }
        }

        val totalScore = totalCorrectAnswer.toDouble() / 100  * totalQuiz

        startActivity<ScoreActivity>(
            ScoreActivity.EXTRA_NICKNAME to nickname,
            ScoreActivity.EXTRA_SCORE to totalScore.toInt()
        )
    ```
    
    c.
    ```java
        val contents = contentAdapter.getResults()
        val totalQuiz = contents.size
        var totalCorrectAnswer = 0

        for (content in contents) {
            for (answer in content.answers!!) {
                totalCorrectAnswer += 1
            }
        }

        val totalScore = totalCorrectAnswer.toDouble() / totalQuiz * 100

        startActivity<ScoreActivity>(
            ScoreActivity.EXTRA_NICKNAME to nickname,
            ScoreActivity.EXTRA_SCORE to totalScore.toInt()
        )
    ```

    **d.
    ```java
        val contents = contentAdapter.getResults()
        val totalQuiz = contents.size
        var totalCorrectAnswer = 0

        for (content in contents) {
            for (answer in content.answers!!) {
                if (answer.isClick == true && answer.correctAnswer == true) {
                    totalCorrectAnswer += 1
                }
            }
        }

        val totalScore = totalCorrectAnswer.toDouble() / totalQuiz * 100

        startActivity<ScoreActivity>(
            ScoreActivity.EXTRA_NICKNAME to nickname,
            ScoreActivity.EXTRA_SCORE to totalScore.toInt()
        )
    ```
    **

57. Source code untuk membuat button next akan pindah index berikutnya sebelum index nya habis ialah...

    a. 
    ```java
        if(currentPosition < dataSize) {
            contentBinding.rvContent.smoothScrollToPosition(currentPosition + 1)
        }
    ```

    b. 
    ```java
        if(currentPosition < dataSize + 1) {
            contentBinding.rvContent.smoothScrollToPosition(currentPosition + 1)
        }
    ```

    **c. 
    ```java
        if(currentPosition < dataSize - 1) {
            contentBinding.rvContent.smoothScrollToPosition(currentPosition + 1)
        }
    ```
    **

    d. 
    ```java
        if(currentPosition < dataSize - 1) {
            contentBinding.rvContent.smoothScrollToPosition(currentPosition - 1)
        }
    ```

## Menampilkan Score di Halaman ScoreActivity dan Melakukan Debug

58. Agar nickname muncul pada halaman score maka perlu menambahkan source code di PrepareActivity yaitu

    a.
    ```java
        prepareBinding.btnStart.setOnClickListener{
            val nickname = prepareBinding.etNickname.text.toString()
            if(checkValidation(nickname)){
                startActivity<ContentActivity>(
                    ContentActivity.EXTRA_NICKNAME
                )
            }
        }
    ```

    b.
    ```java
        prepareBinding.btnStart.setOnClickListener{
            val nickname = prepareBinding.etNickname.text
            if(checkValidation(nickname)){
                startActivity<ContentActivity>(
                    ContentActivity.EXTRA_NICKNAME to nickname
                )
            }
        }
    ```

    **c.
    ```java
        prepareBinding.btnStart.setOnClickListener{
            val nickname = prepareBinding.etNickname.text.toString()
            if(checkValidation(nickname)){
                startActivity<ContentActivity>(
                    ContentActivity.EXTRA_NICKNAME to nickname
                )
            }
        }
    ```
    **

    d.
    ```java
        prepareBinding.btnStart.setOnClickListener{
            val nickname = prepareBinding.etNickname.text.toString()
            startActivity<ContentActivity>(
                ContentActivity.EXTRA_NICKNAME to nickname
            )
        }
    ```

59. Source code untuk membuat logic button back yang benar ialah...

    a.
    ```java
        contentBinding.btnBack.setOnClickListener {
            AlertDialog.Builder(this)
                .setTitle(getString(R.string.are_you_sure))
                .setMessage(getString(R.string.message_exit))
                .setPositiveButton(getString(R.string.yes)){dialog,_->
                    dialog.dismiss()
                    startActivity<MainActivity>()
                }
                .setNegativeButton(getString(R.string.no)){dialog,_->
                    dialog.dismiss()
                }
                .show()
        }
    ```

    b.
    ```java
        contentBinding.btnBack.setOnClickListener {
            AlertDialog.Builder(this)
                .setTitle(getString(R.string.are_you_sure))
                .setMessage(getString(R.string.message_exit))
                .setPositiveButton(getString(R.string.yes)){dialog,_->
                    dialog.dismiss()
                    finishAffinity()
                    startActivity<MainActivity>()
                }
                .setNegativeButton(getString(R.string.no)){dialog,_->
                    dialog.dismiss()
                }
                .show()
        }
    ```

    **c.
    ```java
        contentBinding.btnBack.setOnClickListener {
            AlertDialog.Builder(this)
                .setTitle(getString(R.string.are_you_sure))
                .setMessage(getString(R.string.message_exit))
                .setPositiveButton(getString(R.string.yes)){dialog,_->
                    dialog.dismiss()
                    startActivity<MainActivity>()
                    finishAffinity()
                }
                .setNegativeButton(getString(R.string.no)){dialog,_->
                    dialog.dismiss()
                }
                .show()
        }
    ```
    **

    d.
    ```java
        contentBinding.btnBack.setOnClickListener {
            AlertDialog.Builder(this)
                .setTitle(getString(R.string.are_you_sure))
                .setMessage(getString(R.string.message_exit))
                .setPositiveButton(getString(R.string.yes)){dialog,_->
                    dialog.dismiss()
                }
                .setNegativeButton(getString(R.string.no)){dialog,_->
                    dialog.dismiss()
                    startActivity<MainActivity>()
                    finishAffinity()
                }
                .show()
        }
    ```

60. Source code untuk mendapatkan nickname dan score pada halaman score yaitu...

    a.
    ```java
        //Get Data
        if (intent == null) {
            val score = intent.getIntExtra(EXTRA_SCORE, 0)
            val nickname = intent.getStringExtra(EXTRA_NICKNAME)

            scoreBinding.tvNickname = nickname
            scoreBinding.tvScore = score.toString()
        }
        onClick()
    ```

    **b.
    ```java
        //Get Data
        if (intent != null) {
            val score = intent.getIntExtra(EXTRA_SCORE, 0)
            val nickname = intent.getStringExtra(EXTRA_NICKNAME)

            scoreBinding.tvNickname.text = nickname
            scoreBinding.tvScore.text = score.toString()
        }
        onClick()
    ```
    **

    c.
    ```java
        //Get Data
        if (intent != null) {
            val score = intent.getIntExtra(EXTRA_SCORE, 0)
            val nickname = intent.getStringExtra(EXTRA_NICKNAME)

            scoreBinding.tvNickname = nickname
            scoreBinding.tvScore = score.toString()
        }
        onClick()
    ```

    d.
    ```java
        //Get Data
        if (intent != null) {
            val score = intent.getIntExtra(EXTRA_SCORE, 0)
            val nickname = intent.getStringExtra(EXTRA_NICKNAME)

            scoreBinding.tvNickname = nickname
            scoreBinding.tvScore = score
        }
        onClick()
    ```

# Penutup

## Penutup

61. Aplikasi QuizAPP dapat digabungkan juga dengan database?

    a. firebase

    b. mysql

    c. sqlite

    **d. semua benar**

62. Aplikasi QuizAPP cocok digabungkan dengan aplikasi?

    **a. Elearning**

    b. Toko online

    c. Donasi

    d. Blog 