<template>
  <div id="app">
    <b-navbar toggleable="lg" type="light" variant="light">
    <div class="h2 mb-0">
    <b-icon icon="cart-fill" style="color: #000000;"></b-icon>
    </div>
    <b-navbar-brand href="#">NOBI CHA</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Link</b-nav-item>
        <b-nav-item href="#" disabled>Disabled</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>
        <div id="nav">
          <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template #button-content>
            <em>User</em>
          </template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
        </div>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
    <div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1000px"
    img-height="300px"
  >
    <b-carousel-slide
      caption="หมวดเครื่องดื่มโซดา"
      img-src="https://www.nobicha.co.th/wp-content/uploads/2018/12/soda-pic.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="หมวดชาเขียว"
      img-src="https://www.nobicha.co.th/wp-content/uploads/2018/12/green-tea-pic.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="หมวดชาไทย"
      img-src="https://www.nobicha.co.th/wp-content/uploads/2018/12/thai-tea-pic.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="หมวดโกโก้"
      img-src="https://www.nobicha.co.th/wp-content/uploads/2018/12/cocoa-pic.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="หมวดกาแฟ"
      img-src="https://www.nobicha.co.th/wp-content/uploads/2018/12/coffee-pic.jpg"
    ></b-carousel-slide>
  </b-carousel>
</div>
<div class="container">
  <h2 align="center">ข่าวสารและกิจกรรม</h2>
  <div class="row">
    <div class="col-4 col-3 mt-4">
      <b-card
        title="ใหม่ บุกบราวน์ชูการ์🥳แคลอรี่ต่ำ เคี้ยวสนุก"
        img-src="https://www.nobicha.co.th/wp-content/uploads/2021/02/%E0%B9%83%E0%B8%AB%E0%B8%A1%E0%B9%88-%E0%B8%9A%E0%B8%B8%E0%B8%81%E0%B8%9A%E0%B8%A3%E0%B8%B2%E0%B8%A7%E0%B8%99%E0%B9%8C%E0%B8%8A%E0%B8%B9%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%8C-1536x1530.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
      <b-card-text>
        ต้องลองถึงจะรู้ รู้แล้วบอกเลยหยุดไม่อยู่ ปักหมุดความอร่ิยได้แล้วที่โนบิชาทุกสาขา
      </b-card-text>
      </b-card>
    </div>
    <div class="col-4 col-3 mt-4">
      <b-card
        title="Nobicha 𝐗 Foodpandaมอบสุขสุดๆ"
        img-src="https://www.nobicha.co.th/wp-content/uploads/2021/01/nobicha-x-foodpanda-1527x1536.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
      <b-card-text>
        สั่ง foodpanda วันนี้ ลดเลย ฿100 เพียงใส่โค้ด HOORAY100 เมื่อสั่งครบ ฿200
      </b-card-text>
      </b-card>
    </div>
    <div class="col-4 col-3 mt-4">
      <b-card
        title="เดลิเวอรี่ห่วงใยแถมยังได้ 𝐒𝐓𝐀𝐘 𝐒𝐀𝐅𝐄 ที่บ้าน!"
        img-src="https://www.nobicha.co.th/wp-content/uploads/2021/01/%E0%B9%80%E0%B8%94%E0%B8%A5%E0%B8%B4%E0%B9%80%E0%B8%A7%E0%B8%AD%E0%B8%A3%E0%B8%B5%E0%B9%88%E0%B8%AB%E0%B9%88%E0%B8%A7%E0%B8%87%E0%B9%83%E0%B8%A2-%E0%B9%81%E0%B8%96%E0%B8%A1%E0%B8%A2%E0%B8%B1%E0%B8%87%E0%B9%84%E0%B8%94%E0%B9%89-%F0%9D%90%92%F0%9D%90%93%F0%9D%90%80%F0%9D%90%98-%F0%9D%90%92%F0%9D%90%80%F0%9D%90%85%F0%9D%90%84-%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%9A%E0%B9%89%E0%B8%B2%E0%B8%99-1536x1536.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
      <b-card-text>
        ด้วยความห่วงใยจากน้องโนบิสามารถสั่งผ่านช่องทาง 𝐃𝐞𝐥𝐢𝐯𝐞𝐫𝐲
      </b-card-text>
      </b-card>
    </div>
    <div class="col-4 col-3 mt-4">
      <b-card
        title="ท๊อปปิ้ง โนบิชา เริ่มต้น 5 บาท"
        img-src="https://www.nobicha.co.th/wp-content/uploads/2020/12/%E0%B8%97%E0%B9%8A%E0%B8%AD%E0%B8%9B%E0%B8%9B%E0%B8%B4%E0%B9%89%E0%B8%87-%E0%B9%82%E0%B8%99%E0%B8%9A%E0%B8%B4%E0%B8%8A%E0%B8%B2-%E0%B9%80%E0%B8%A3%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B8%95%E0%B9%89%E0%B8%99-5-%E0%B8%9A%E0%B8%B2%E0%B8%97.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
      <b-card-text>
        ใส่คู่กับเครื่องดื่มอะไร ก็เข้ากันดี…
      </b-card-text>
      </b-card>
    </div>
    <div class="col-4 col-3 mt-4">
      <b-card
        title="มาแล้ว พิเศษสุดคุ้ม!!!"
        img-src="https://www.nobicha.co.th/wp-content/uploads/2020/12/%E0%B8%84%E0%B8%A3%E0%B8%B5%E0%B8%A1%E0%B9%80%E0%B8%97%E0%B8%B5%E0%B8%A2%E0%B8%A1-%E0%B9%82%E0%B8%99%E0%B8%9A%E0%B8%B4%E0%B8%8A%E0%B8%B2.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
      <b-card-text>
        ครีมเทียม ตราโนบิชา Nobi cha Creamer ลังละ 700 บาท 
      </b-card-text>
      </b-card>
    </div>
    <div class="col-4 col-3 mt-4">
      <b-card
        title="ใหม่ในใหม่!!! ไม่เหมือนใคร มีเฉพาะ “โนบิชา” เท่านั้น"
        img-src="https://www.nobicha.co.th/wp-content/uploads/2020/08/%E0%B9%83%E0%B8%AB%E0%B8%A1%E0%B9%88-%E0%B9%84%E0%B8%82%E0%B9%88%E0%B8%A1%E0%B8%B8%E0%B8%81%E0%B8%84%E0%B8%A3%E0%B8%B4%E0%B8%AA%E0%B8%95%E0%B8%B1%E0%B8%A5-Crystal-Pearl-%E0%B8%81%E0%B8%A5%E0%B8%B4%E0%B9%88%E0%B8%99%E0%B8%A1%E0%B8%B0%E0%B8%9E%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%A7.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
      <b-card-text>
        ไข่มุกคริสตัล (Crystal Pearl) กลิ่นมะพร้าว
      </b-card-text>
      </b-card>
    </div>
  </div>
</div>
<div class="container">
  <h2 align="center">ข่าวสารและกิจกรรม</h2>
  <div class="row">
    <div class="col-md-2" v-for="item in products">
      <div class="card h-100">
        <img :src="item.image" class="card-img-top">
          <div class="card-body">
              <h4 class="card-title">{{item.name}}</h4>
              <p class="card-text">ราคา {{item.price}} บาท</p>
          </div>
          <div class="card-footer">
              <button class="btn btn-primary" @click="addCart(item)">หยิบลงตะกร้า</button>
          </div>
          </div>
    </div>
    <div class="col-md-8" v-if="carts!=0">
    <h4>
      ตะกร้าสินค้า
    <i class="fa fa-shopping-cart"></i>
    </h4>
    <hr>
    <table class="table">
    <thead class="thead-dark">
      <tr>
        <th scope="col">ภาพ</th>
        <th scope="col">ชื่อ</th>
        <th scope="col">ราคา</th>
        <th scope="col">จำนวน</th>
        <th scope="col">ยอดรวม</th>
        <th scope="col">ลบ</th>
      </tr>
    </thead>
    <tbody>
      <tr v-for="product in carts">
      <td>
        <img :src="product.image" alt="" width="80px" height="100px">
      </td>
      <td>{{product.name}}</td>
      <td>{{product.price}}</td>
      <td>
        <i class="fa fa-minus qty-minus" @click="minusQty(product)"></i>
            {{product.qty}}
            <i class="fa fa-plus qty-plus" @click="plusQty(product)"></i>
      </td>
      <td>{{product.total}}</td>
      <td>
        <button @click="removeProduct(product)" class="btn-danger">
          <i class="fa fa-trash"></i>
        </button>
      </td>
      </tr>
      </tbody>
      </table>
        <h4 align="right">ยอดชำระเงิน {{total()}} บาท</h4>
    </div>
    </div>
</div>   
</div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      carts:[],
      coffee:0,
      tea:0,
      products:[
        {
          id:1,
          name:"กาแฟเย็น",
          price:25,
          image:"https://www.nobicha.co.th/wp-content/uploads/2018/12/nescafe.png",
          active:false
        },
        {
          id:2,
          name:"ชาเย็น",
          price:19,
          image:"https://www.nobicha.co.th/wp-content/uploads/2018/12/thai-milk-tea.png",
          active:false
        }
      ]
    }
  },
  methods:{
      addCart:function(item){
          if(item.id==1){
            // ซื้อกาแฟ
            this.coffee+=1;
            if(this.coffee<=1){
             //ซื้อรอบเดียว
              this.pushData(item)
            }else{
             //รายการเดียวกัน
              var found = this.findIndex(item);
              this.carts[found].qty+=1;
              this.carts[found].total=this.carts[found].qty * this.carts[found].price;
            }
          }else{
            //ซื้อชาเย็น
            this.tea+=1;
            if(this.tea<=1){
             //ซื้อรอบเดียว
              this.pushData(item)
            }else{
             //รายการเดียวกัน
              var found = this.findIndex(item);
              this.carts[found].qty+=1;
              this.carts[found].total=this.carts[found].qty * this.carts[found].price;
            }
          }
      },
      pushData(item){
         this.carts.push({
              id:item.id,
              name:item.name,
              price:item.price,
              image:item.image,
              qty:1,
              total:item.price
          })
      },
      findIndex:function(item){
          for(var i = 0;i<this.carts.length;i++){
             if(this.carts[i].id == item.id){
                return i; //ตำแหน่งสินค้าที่ค้นเจอในตะกร้า
             }
          }
          return -1;
      },
      minusQty:function(product){
          product.qty-=1;
          if(product.qty<=1){
              product.qty=1
          }
          product.total=product.price*product.qty;
      },
      plusQty:function(product){
          product.qty+=1;
          product.total=product.price*product.qty;
      },
      removeProduct(product){
          if(confirm("คุณต้องการลบหรือไม่ ?")){
              var index=this.carts.indexOf(product);
              this.carts.splice(index,1);
              if(product.id==1){
                 this.coffee=0;
              }else{
                  this.tea=0;
              }
          }
      },
      total:function(){
         var sum=0;
         this.carts.forEach(function(item){
            sum+=item.total;
         })
         return sum;
      }
  }
}
</script>
<style  scoped>
.qty-minus{
    cursor: pointer;
    margin-right: 20px;
}
.qty-plus{
    cursor: pointer;
    margin-left: 20px;
}
</style>

