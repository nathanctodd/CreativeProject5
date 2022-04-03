<template>
<div class="admin">
    <h1>Alpine Ski Equipment</h1>
    <div class="heading">

    </div>
    <div class="add">
      <div class="form">
        

        <div class="productList">
    <div class="productThreesome">
      <div class="photoitem">
        <img class="realitem" src="/images/Ski6.jpg.webp">
        <div class="photoText">Nordica F255</div>
        <div class="price">Starting at $799</div>
        <button @click="upload('Nordica F55','$799')">Add to Cart</button>
      </div>
        <div class="photoitem">
        <img class="realitem" src="/images/Ski2.webp">
        <div class="photoText">Nordica E33</div>
        <div class="price">Starting at $799</div>
        <button @click="upload('Nordica E33','$799')">Add to Cart</button>
      </div>
        <div class="photoitem">
        <img class="realitem" src="/images/Ski5.jpg.webp">
        <div class="photoText">Volkel 55L</div>
        <div class="price">Starting at $999</div>
        <button @click="upload('Volkel 55L','$999')">Add to Cart</button>
      </div>
      <div style="padding-top: 200px;"></div>
    </div>
  
    <div class="productThreesome">
      <div class="photoitem">
        <img class="realitem" src="/images/Ski4.jpg.webp">
        <div class="photoText">Rosignol AR42</div>
        <div class="price">Starting at $759</div>
        <button @click="upload('Rosignol AR42','$759')">Add to Cart</button>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Ski3.jpg.webp">
        <div class="photoText">Ripper PLUS</div>
        <div class="price">Starting at $9999</div>
        <button @click="upload('Ripper PLUS','$9999')">Add to Cart</button>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Ski1.jpg.webp">
        <div class="photoText">Snowplow P60s</div>
        <div class="price">Starting at $899</div>
        <button @click="upload('Snowplow P60s','$899')">Add to Cart</button>
      </div>
      <div style="padding-top: 200px;"></div>
    </div>

    <div class="productThreesome">
      <div class="photoitem">
        <img class="realitem" src="/images/Ski7.jpg.webp">
        <div class="photoText">Snowcat Y508</div>
        <div class="price">Starting at $799</div>
        <button @click="upload('Snowcat Y508','$799')">Add to Cart</button>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Ski5.jpg.webp" style="opacity: 0.0;">
        <div class="photoText"></div>
        <div class="price"></div>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Ski6.jpg.webp" style="opacity: 0.0;">
        <div class="photoText"></div>
        <div class="price"></div>
      </div>
      <div style="padding-top: 100px;"></div>
    </div>

  <div style="padding-top: 100px;"></div>
  <div class="sectionTitle">Alpine Ski Boots</div>

    <div class="productThreesome">
      <div class="photoitem">
        <img class="realitem" src="/images/Boots1.jpg">
        <div class="photoText">Rosignol AR42</div>
        <div class="price">Starting at $499</div>
        <button @click="upload('Rosignol AR42','$499')">Add to Cart</button>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Boots5.jpg">
        <div class="photoText">Atomic Boots</div>
        <div class="price">Starting at $399</div>
        <button @click="upload('Atomic Boots','$399')">Add to Cart</button>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Boots3.jpg">
        <div class="photoText">Snowplow Boots</div>
        <div class="price">Starting at $349</div>
        <button @click="upload('Snowplot Boots','$349')">Add to Cart</button>
      </div>
      <div style="padding-top: 100px;"></div>
    </div>

    <div class="productThreesome">
      <div class="photoitem">
        <img class="realitem" src="/images/Boots4.jpg">
        <div class="photoText">Snowcat Boots</div>
        <div class="price">Starting at $399</div>
        <button @click="upload('Snowcat Boots','$399')">Add to Cart</button>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Boots4.jpg" style="opacity: 0.0;">
        <div class="photoText"></div>
        <div class="price"></div>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Boots4.jpg" style="opacity: 0.0;">
        <div class="photoText"></div>
        <div class="price"></div>
      </div>
      <div style="padding-top: 200px;"></div>
    </div>

    <div style="padding-top: 100px;"></div>
    <div class="sectionTitle">Alpine Ski Poles</div>

    <div class="productThreesome">
      <div class="photoitem">
        <img class="realitem" src="/images/Poles1.webp">
        <div class="photoText">K2 Carbon Ski Poles</div>
        <div class="price">Starting at $49</div>
        <button @click="upload('K2 Carbon Ski Poles','$49')">Add to Cart</button>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Poles2.webp">
        <div class="photoText">Carbon Fiber Poles</div>
        <div class="price">Starting at $39</div>
        <button @click="upload('Carbon Fiber Poles','$39')">Add to Cart</button>
      </div>
      <div class="photoitem">
        <img class="realitem" src="/images/Poles1.webp">
        <div class="photoText">P3 Ski Poles</div>
        <div class="price">Starting at $49</div>
        <button @click="upload('P3 Ski Poles','$49')">Add to Cart</button>
      </div>
      <div style="padding-top: 100px;"></div>
    </div>
    <div style="padding-top: 100px;"></div>
    <div class="browse">
    </div>
  </div>        
      </div>
    </div>
        <div style="padding-top: 100px;"></div>
    <div style="padding-top: 100px;"></div>


  <div style="height: 200px; background-color: gray; display: flex; justify-content: center;">
    <div style="display: flex; justify-content: center; align-items: center;">
      <a style="color: black; display: flex;" href="https://github.com/nathanctodd/CreativeProject5">Github  |  CreativeProject5  |  Nathan Todd</a>
    </div>
  </div>
  </div>
</template>


<script> 
  import axios from 'axios';
  export default {
    name: 'Admin',
    data() {
      return {
        title: "",
        file: null,
        addItem: null,
        items: [],
        findTitle: "",
        findItem: null,
        findDescription: "",
        price: "",
      }
    },
     computed: {
      suggestions() {
        let items = this.items.filter(item => item.title.toLowerCase().startsWith(this.findTitle.toLowerCase()));
        return items.sort((a, b) => a.title > b.title);
      
      }
    },
    created() {
      this.getItems();
    },
    methods: {
      fileChanged(event) {
        this.file = event.target.files[0]
      },
      async upload(name, price) {
        try {
          let r2 = await axios.post('/api/items', {
            title: name,
            price: price,
          });
          this.addItem = r2.data;
          console.log(name, price)  
        } catch (error) {
          console.log(error);
        }
      },
      async getItems() {
        try {
          let response = await axios.get("/api/items");
          this.items = response.data;
          return true;
        } catch (error) {
          console.log(error);
        }
      },
       selectItem(item) {
        this.findTitle = "";
        this.findDescription = "";
        this.findItem = item;
      },
      async deleteItem(item) {
        try {
          await axios.delete("/api/items/" + item._id);
          this.findItem = null;
          this.getItems();
          return true;
        } catch (error) {
          console.log(error);
        }
      },
      async editItem(item) {
        try {
          console.log("Bro");
          await axios.put("/api/items/" + item._id, {
            title: this.findItem.title,
            price: this.findItem.price,
          });
          this.findItem = null;
          this.getItems();
          return true;
        } catch (error) {
          console.log(error);
        }
      },
    }
  }
</script>



<style scoped>
.image h2 {
  font-style: italic;
  font-size: 1em;
}

h1 {
  font-size: 40px;
}

.heading {
  display: flex;
  margin-bottom: 20px;
  margin-top: 20px;
}

.heading h2 {
  margin-top: 8px;
  margin-left: 10px;
}

.add,
.edit {
  display: flex;
}

.circle {
  border-radius: 50%;
  width: 18px;
  height: 18px;
  padding: 8px;
  background: #333;
  color: #fff;
  text-align: center
}

/* Form */
input,
textarea,
select,
button {
  font-family: 'Montserrat', sans-serif;
  font-size: 1em;
}

.descriptionclass {
  width: 50%;
}

.form {
  margin-right: 50px;
}

/* Uploaded images */
.upload h2 {
  margin: 0px;
}

.upload img {
  max-width: 300px;
}

.suggestions {
  width: 200px;
  border: 1px solid #ccc;
}

.suggestion {
  min-height: 20px;
}

.suggestion:hover {
  background-color: #5BDEFF;
  color: #fff;
}

.page {
    display: flex;
    width: 100%;

}

.background {
    display: flex;
    width: 100%;
}

.backgroundImage {
    display: flex;
    width: 100%;
    height: auto;
}

.text {
    display: flex;
    width: 100%;
    position: absolute;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.titleText {

    display: flex;
    color: rgb(105, 104, 104);
    font-size: 200px;

}

.message {
    display:flex;
    color: rgb(103, 103, 103);
    font-size: 50px;
}

.productShowcase {
    display: flex;
    width: 100%;
    flex-direction: column;
    justify-content: center;
}

.skis {
    display: flex;
    width: 100%;
    justify-content: center;
}
.boots {
    display: flex;
    width: 100%;
    justify-content: center;
}
.poles {
    display: flex;
    width: 100%;
    justify-content: center;
}

.photo {
    display: flex;
    padding-left: 800px;
    padding-right: 100px;
}
.skiphoto {
    display: flex;
    width: 100%;
    padding: 50px;
}

.skiLink {
    width: 100%;
}
.skiLink:hover {
    color:rgb(62, 62, 62)
}

.skitext {

    display: flex;
    width: 100%;   
    justify-content: center;
    flex-direction: column; 

}
.skiTitle {
    display: flex;
    width: 60%;
    color: rgb(68, 68, 68);
    font-size: 125px;
}
.skiMessage {
    display: flex;
    width: 60%;
    color: rgb(74, 74, 74);
    font-size: 50px;
}
.boottext {
    display: flex;
    width: 50%;
    justify-content: center;
    flex-direction: column;
    padding-left: 600px;
}
.bootTitle {
    display: flex;
    width: 60%;
    color: rgb(68, 68, 68);
    font-size: 125px;
}
.bootMessage {
    display: flex;
    width: 60%;
    color: rgb(74, 74, 74);
    font-size: 50px;
}

.bootphoto {
    display: flex;
  
}
.bootphotoitem {
    display: flex;
    width: 100%;
    padding:100px;
    padding-right: 600px;
}

.poletext {
    display: flex;
    width: 100%;   
    justify-content: center;
    flex-direction: column; 
    padding-left: 200px;

}
.poleTitle {
    display: flex;
    width: 60%;
    color: rgb(68, 68, 68);
    font-size: 125px;
}
.poleMessage {
    display: flex;
    width: 60%;
    color: rgb(74, 74, 74);
    font-size: 50px;
}

.poles {
    display: flex;
    padding-left: 600px;
    padding-right: 350px;
}
.polePhotoItem {
    display: flex;
    width: 140%;
    padding: 200px;
    padding-right: 500px;
}

.browse {
    display: flex;
    font-size: 100px;
    color:rgb(62, 62, 62);
    border-radius: 10px;
    justify-content: center;
    width: 100%;
}
.productLink {
    display: flex;
    background-color: rgb(226, 226, 226);
    font-size: 40px;
    color:rgb(62, 62, 62);
    border-radius: 20px;
    padding: 30px;
    padding-left: 60px;
    padding-right: 60px;
}

.productLink:hover {
    
    color:rgb(119, 119, 119);
 
}

/* PRODUCTS  */

.screenPage, .backgroundImage, .productText {
    display: flex;
    width: 100%;
}

.screenPage {
    display: flex;
    justify-content: center;
}

.openingImage {
    display: flex;
    width: 100%;
    height: auto;

}

.productText {
    justify-content: center;
    align-items: flex-start;
    display: flex;
    position: absolute;
    height: 100%;
}

.productTitles {
    position: absolute;
    display: flex;
    font-size: 200px;
    color: rgb(253, 253, 253);
    padding: 200px;
}

.productTitle2 {
    position: absolute;
    display: flex;
    font-size: 200px;
    color: rgb(66, 66, 66);
    padding: 200px;
    font-weight: bold;
}

.productList {
    display: flex;
    width: 100%;
    flex-direction: column;
    align-content: center;
}

.productThreesome {
    display: flex;
    width: 100%;
    flex-direction: row;
    justify-content: center;
    justify-content: center;
}

.photo-item {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 800px;
    width: 33%;
}

.realitem {
    display: flex;
    width: 100%;
    height: auto;
    padding: 50px;
}



.sectionTitle {
    font-size: 50px;
    font-weight: bold;
    padding-bottom: 100px;
    padding-left: 100px;
    justify-content: center;
    justify-self: center;
}
.sectionTitle2 {
    font-size: 80px;
    padding-left: 100px;
    font-weight: bold;
    justify-content: center;
    justify-self: center;
}

.starting-image {
    display: flex;
    justify-content: center;
    width: 100%;
    align-items: center;
}

.backdrop {
    display: flex;
    justify-content: center;
    width: 100%;
    height: auto;
}

.aboutus {
    position: absolute;
    display: flex;
    justify-content: center;
    width: 100%;
}

.aboutus2 {
    position: absolute;
    display: flex;
    justify-content: center;
    font-size: 200px;
    color: rgb(73, 73, 73);
    width: 100%;
    font-weight: bolder;
    transform: translate(0%, -200%);

}

.textboxes {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%;
}

.title-about {
    display: flex;
    justify-content: center;
    font-size: 125px;
    color:rgb(56, 56, 56);
    font-weight: bold;
    padding: 100px;
    width: 56%;
}

.title-message {
    width: 50%;
    display: flex;
    justify-content: center;
    font-size: 60px;
    color:rgb(76, 76, 76);
    font-weight: lighter;
    padding: 0px;
}

.photoText {

    display: flex;
    width: 100%;
    font-size: 50px; 
    color:rgb(62, 62, 62);
    text-align: center;
    justify-content: center;
    padding: 20px;
}
.price {

    display: flex;
    width: 100%;
    font-weight: lighter;
    color: rgb(36, 52, 101);
    text-align: center;
    justify-content: center;
    font-size: 30px;
    padding: 0px;
    align-items: flex-end;
}


.checkoutitem {
    display: flex;
    width: 80%;
    justify-content: center;
    justify-self: center;
    flex-direction: row;
    background-color: rgb(227, 227, 227);
    border-radius: 30px;
    padding: 20px;
    
}

.checkouttitle {
    font-size: 50px;
    font-weight: bold;
    color:rgb(47, 47, 47);
    display: flex;
}
.checkout2 {

    display: flex;
    justify-content: center;
    padding: 40px;

}
.checkoutprice {
    font-size: 40px;
    font-weight: lighter;
    color:rgb(47, 47, 47);
    display: flex;
}

.screenPage2 {
    display: flex;
    justify-content: center;
    width: 100%;
}
.skitext2 {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    width: 100%;

}
.checkoutphoto {
    display: flex;
    justify-content: center;    
}

.checkoutphotoitem {
    display: flex;
    justify-content: center; 
    width: 300px;
    height: auto;   
    border-radius: 20.0px;
}


.namefield {
    width: 30%;
    display: flex;
    background-color: rgb(220, 220, 220);
    justify-content: center;
    align-items: center;
    margin: 50px;
    border-radius: 10px;
    text-align: left;
    font-size: 30px;
    height: 80px;
}

.creditcard {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    width: 100%;
}

.address {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    width: 100%;
}

.creditcardnumberfield {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 40%;
    margin: 30px;
    border-radius: 10px;
    text-align: left;
    background-color: rgb(220, 220, 220);
    font-size: 30px;
    height: 80px;
}

.creditcardnumberfield2 {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 20%;
    margin: 30px;
    border-radius: 10px;
    text-align: left;
    background-color: rgb(220, 220, 220);
    font-size: 30px;
    height: 80px;
}

.creditcardnumberfield3 {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 10%;
    margin: 30px;
    border-radius: 10px;
    text-align: left;
    background-color: rgb(220, 220, 220);
    font-size: 30px;
    height: 80px;
}

.address1 {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 50%;
    margin: 30px;
    border-radius: 10px;
    text-align: left;
    background-color: rgb(220, 220, 220);
    font-size: 30px;
    height: 80px;
}

.address2 {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 8%;
    margin: 30px;
    border-radius: 10px;
    text-align: left;
    background-color: rgb(220, 220, 220);
    font-size: 30px;
    height: 80px;
}

.address3 {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 12%;
    margin: 30px;
    border-radius: 10px;
    text-align: left;
    background-color: rgb(220, 220, 220);
    font-size: 30px;
    height: 80px;
}



/* FOOTER  */
.footer {

    width: 100%;
    height: 500px;
    background-color: #343a3f;
    display: flex;
    flex-direction: column;

  }

  .link {

    padding-bottom: 100px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    height: 100%;
  }

  .icons {

    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 200px;

  }

  .photo-icon {

    display: flex;
    width: 200px;
    height: auto;
    padding: 40px;
    padding-bottom: 70px;

  }
  
  .githublink {

    align-items: flex-end;
    display: flex;
    font-size: 30px;
    color: white;

  }
  .githublink:hover {
    color: gray;
  }

</style>