# syntax basic

**a**
```vue
 <html>
    <head>
        <title>Vue JS Template</title>
        <script src="vue.js"></script>
        <link rel="stylesheet" href="style.css">
    </head>
        <div id="object">
            <!-- <div v-on:mousemove="Toado">
                <p v-html="testHTML"></p>
                <p v-once>
                    {{content}} {{showpost()}}</p>
                </p> -->
                <!-- <p>{{ sayhi() }}</p>
                <p>{{ showpost() }}</p>
                <a v-bind:href="link">Google</a> -->
                <!-- <h1>Bam nut de tang gia tri</h1>
                <button v-on:click="tanggiatri">An</button>
                <button v-on:click="dem--">An theo js</button>
                <p>gia tri sau dem:{{dem}}</p>
                <p>gia tri sau dem:{{dem > 20 ? "ban da vuot qua muc gioi han" : "ban van nam trong gioi han"}}</p>
                <p v-on:mouseover.stop="">dung su kien</p>
                <p >toa do cua chuot:{{ x }} / {{ y }}</p>
            </div> -->
            <!-- <div id="class">
                <input type="text" @keyup.enter.space="keyboard">
            </div> -->
            <!-- <input type="text" v-on:input="change">
            <input type="text" v-on:model="name">
            <p>{{name}}</p> -->
            <!-- <p>gia tri A:{{ tanga }}</p>
            <p>gia tri B:{{ tangb }}</p>
            <p>gia tri A:{{ tangaf() }}</p>
            <p>gia tri B:{{ tangbf() }}</p>
            <button v-on:click="a++">Tang A</button>
            <button v-on:click="b++">Tang B</button> -->
            <!-- <p>{{ diem }}</p> -->
            <!-- <button @click="changelink">click to change</button>
            <a v-bind:href="link">Link</a> -->
            <div class="vuong" @click="maudo = !maudo" :class="{red: maudo}"></div>
            <div class="vuong" :class="{red: maudo}"></div>
            
            
            
            <div class="vuong" :class="[color, {red: maudo}]"></div>
            <hr>
            <input type="text" v-model="color">
        </div>


        <script>
           //computed chay truoc methods
           //computed thuc hien nhu mot function nhung no chi duoc coi nhu mot thuoc tinh
           //tat ca du lieu chuyen qua HTML deu o dang du lieu tho (text)
            //phan biet click giua cac o voi click, neu khong phai o thu 3 thi chuyen het sang mau do, con click vao o 3 thi chuyen sang mau xanh
            var app = new Vue({
                el:"#object",
                data: {
                    // name: "sky",
                    // content:"Xin chao",
                    // link: "https://www.facebook.com/?locale=vi_VN",
                    // testHTML: "<a href='http....'> Get password </a>",
                    // dem: 0,
                    // x: 0,
                    // y: 0,
                    // a: 0,
                    // b: 0,
                    // diem: "ban A co mon toan 7 diem"
                    // link:"https://www.facebook.com"
                    maudo: false,
                    color: 'green',
                },
                computed: {
                    // tanga: function(){
                    //     console.log("goi function a");
                    //     return this.a;
                    // },
                    // tangb: function(){
                    //     console.log("goi function b");
                    //     return this.b;
                    // }
                    divClasses: function(){
                        return {
                            red: this.maudo,
                            blue: !this.maudo
                        }
                    }

                },
                watch:{
                    // diem: function(newvalue){
                    //     alert("diem cua ban da duoc cap nhat");
                    // }
                },
                methods:{
                    // change: function(event) {
                    //     this.name = event.target.value;
                    // }
                    // sayhi: function(){
                    //     document.write("xhi ngasi");
                    // },
                    // showpost: function(){
                    //     this.content = " tat ca cac ban";
                    //     return this.content;
                    // },
                    // tanggiatri: function(){
                    //     this.dem++;
                    // },
                    // Toado: function(event){
                    //     this.x = event.clientX;
                    //     this.y = event.clientY;
                    // },
                    // keyboard: function(){
                    //     alert("keyboard");
                    // }
                    // tangaf: function(){
                    //     console.log("goi function af");
                    //     return this.a;
                    // },
                    // tangbf: function(){
                    //     console.log("goi function bf");
                    //     return this.b;
                    // },
                    // changelink: function(){
                    //     this.link = 'https://www.google.com.vn/?hl=vi';
                    // },
                },
            });
            // app.diem = "ban A co diem mon toan la 8"
        </script>
</html>
```
 ghggjgjgj
 kljlkljl>
 > asdasasdasdfasg 