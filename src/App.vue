<template>
  <div id="app">
    <div class="cv1 row" style="padding: 40px;">
      <div class="border1">
        <h1 class="card-title">
          Mala <br><span style="color: red"> Fillatunnida</span>
        </h1>
        <img
          src="https://sindunesia.com/wp-content/uploads/2021/01/muslimah-sedang-berbicara-di-telephon.jpg"
          width="300px"
          height="180px"
        />
        <h2>Contact</h2>
        <hr />
        <h3>Address:</h3>
          <p v-for="row in users" :key="row">{{ row.address }}</p>
        <h3>Phone:</h3>
          <p v-for="row in users" :key="row">{{ row.phone }}</p>
        <h3>Email:</h3>
          <p v-for="row in users" :key="row"><u>{{ row.email }}</u></p>
        <h2>Languanges</h2>
        <hr />
          <p v-for="row in users" :key="row">{{ row.languanges1 }}</p>
          <p v-for="row in users" :key="row">{{ row.languanges2 }}</p>
        <h2>Hobbies</h2>
        <hr />
        <ul>
          <li><p v-for="row in users" :key="row">{{ row.hobbies1 }}</p></li>
          <li><p v-for="row in users" :key="row">{{ row.hobbies2 }}</p></li>
        </ul>
      </div>

      <div class="border2">
        <h2>Summary</h2>
        <hr />
          <p v-for="row in users" :key="row">{{ row.summary }}</p>

        <h2>Skill Highlights</h2>
        <hr />
        <ul>
          <li><p v-for="row in users" :key="row">{{ row.skillHighlight1 }}</p></li>
          <li><p v-for="row in users" :key="row">{{ row.skillHighlight2 }}</p></li>
          <li><p v-for="row in users" :key="row">{{ row.skillHighlight3 }}</p></li>
          <li><p v-for="row in users" :key="row">{{ row.skillHighlight4 }}</p></li>
        </ul>

        <h2>Organization Experience</h2>
        <hr />
        <h4 v-for="row in users" :key="row">{{ row.org1 }} <br> {{ row.org2 }}</h4>
        <ul>
          <li><p v-for="row in users" :key="row">{{ row.organizationExperience1 }}</p></li>
          <li><p v-for="row in users" :key="row">{{ row.organizationExperience2 }}</p></li>
          <li><p v-for="row in users" :key="row">{{ row.organizationExperience3 }}</p></li>
        </ul>

        <h2>Educational Background</h2>
        <hr />
            <p v-for="row in users" :key="row">{{ row.educationalBackground1 }}</p>
            <p v-for="row in users" :key="row">{{ row.educationalBackground2 }}</p>
            <p v-for="row in users" :key="row">{{ row.educationalBackground3 }}</p>

        <h2>Achievement</h2>
        <hr />
            <p v-for="row in users" :key="row">{{ row.achievement1 }}</p>
            <p v-for="row in users" :key="row">{{ row.achievement2 }}</p>
            <p v-for="row in users" :key="row">{{ row.achievement3 }}</p>
      </div>
    </div>

    <div class="cv2" style="padding: 40px;">
    
        <div class="head">
        <fieldset class="resume"><legend>&ensp;RESUME&ensp;</legend></fieldset>        
        <h1 style="font-family: times new roman; text-align: left; color: white; margin-left: 390px;"> MALA <br /><span> FILLATUNNIDA</span></h1>
        </div>

        <h2 style="text-align: center; width: 1020px;">PERSONAL DATA</h2>
        <hr style="border: 1px solid black; width: 840px; float: right;">

      <div class="border3">
        <img src="https://ajaib-wp-s3-artifact.s3.ap-southeast-1.amazonaws.com/prd/wp-content/uploads/2019/12/wanita-muslimah-inspiratif.jpg" style="border: 10px solid white; border-radius: 100%; width: 180px; height: 180px;margin-top: -180px;"/>

        <h2>PROFILE</h2>
        <hr style="border: 1px dashed" />
        <p><b>NAME</b></p>
        <p v-for="row in users" :key="row">{{ row.name }}</p>
        <p><b>DATE OF BIRTH</b></p>
        <p v-for="row in users" :key="row">{{ row.date }}</p>
        <p><b>ADDRESS</b></p>
        <p v-for="row in users" :key="row">{{ row.address }}</p>
        <p><b>WEBSITE</b></p>
        <p v-for="row in users" :key="row">{{ row.website }}</p>

        <h2>AWARDS</h2>
        <hr style="border: 1px dashed" />
        <p><b>CHARTER AWARD 2012 </b></p>
        <p v-for="row in users" :key="row">{{ row.character }}</p>
        <p><b>INTERFACE DESIGN 2013 </b></p>
        <p v-for="row in users" :key="row">{{ row.interface }}</p>

        <h2>CONTACT</h2>
        <hr style="border: 1px dashed" />
        <p><b> HOME NUMBER &#9742;</b></p>
        <p v-for="row in users" :key="row">{{ row.home }}</p>
        <p><b>PHONE NUMBER &#x1F4DE;</b></p>
        <p v-for="row in users" :key="row">{{ row.phone }}</p>
        <p><b>EMAIL &#x1F4E7;</b></p>
        <p v-for="row in users" :key="row">
          <u>{{ row.email }}</u>
        </p>

        <h2>SOCIAL</h2>
        <hr style="border: 1px dashed" />
        <p><b>TWITTER</b></p>
        <p v-for="row in users" :key="row">{{ row.twitter }}</p>
        <p><b>FACEBOOOK </b></p>
        <p v-for="row in users" :key="row">{{ row.facebook }}</p>
      </div>

      <div class="border4">
        <div id="p">
          <h2>&#x1F550; WORDS OF WISDOM </h2>
          <hr style="border: 1px dashed" />
          <div class="wr">
          <h3>SUNDAY, 1 OCTOBER 2021</h3>
              <p v-for="row in users" :key="row">{{ row.word1 }}</p>
          </div>
          <div class="wr">
          <h3>MONDAY, 2 OCTOBER 2021</h3>
              <p v-for="row in users" :key="row">{{ row.word2 }}</p>
          </div>
          <div class="wr">
          <h3>TUESDAY, 3 OCTOBER 2021</h3>
              <p v-for="row in users" :key="row">{{ row.word3 }}</p>
          </div>
        </div>
        <br />
        <div id="p">
          <h2>ACHIEVEMENT &#x1F4DD;</h2>
          <hr style="border: 1px dashed" />
          <div class="ac">
            <h3>COMPETITION 2016</h3>
              <p v-for="row in users" :key="row">{{ row.achievement1 }}</p>
          </div>
          <div class="ac">
            <h3>COMPETITION 2016</h3>
              <p v-for="row in users" :key="row">{{ row.achievement2 }}</p>
          </div>
          <div class="ac">
            <h3>COMPETITION 2018</h3>
              <p v-for="row in users" :key="row">{{ row.achievement3 }}</p>
          </div>
        </div>
        <br />
          <div id="p">
          <h2>&#x1F4A1; SKILLS </h2>
          <hr style="border: 1px dashed" />
          <div class="skil">
          <h3>PROFESSIONAL SKILLS</h3>
          <p v-for="row in users" :key="row">{{ row.skill1 }}&nbsp; &#9899; &#9899; &#9899;</p>
          <p v-for="row in users" :key="row">{{ row.skill2 }}&nbsp; &#9899; &#9899; &#9899;</p>
          <p v-for="row in users" :key="row">{{ row.skill6 }}&nbsp; &#9899; &#9899; &#9899;</p>
          </div>
     
          <div class="skil">
          <h3>PERSONAL SKILLS</h3>
          <p v-for="row in users" :key="row">{{ row.skill3 }}&nbsp; &#9899; &#9899; &#9899;</p>
          <p v-for="row in users" :key="row">{{ row.skill4 }}&nbsp; &#9899; &#9899; &#9899;</p>
          <p v-for="row in users" :key="row">{{ row.skill5 }}&nbsp; &#9899; &#9899; &#9899;</p>
          </div>
          </div>

        <br />
      </div>
    </div>
  </div>
</template>

<script>
/* eslint-disable */
import axios from "axios";
export default {
  data() {
    return {
      users: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("http://localhost:3000/users")
        .then((res) => {
          this.users = res.data; //respon dari rest api dimasukan ke users
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
};
</script>


<style scoped>
.resume { 
border-top: 10px solid white;
color: white; 
border-left: none; 
border-bottom: none;
border-right: none; 
margin-bottom: 10px;
}

.border1 {
  border: 1px solid lightgrey;
  padding: 20px;
  width: 300px;
  background-color: lightgrey;
  float: left;
}

.border2 {
  border: 1px solid white;
  padding: 20px;
  background-color: white;
  float: left;
  width: 60%;
  height: 894px;
  margin-bottom: 50px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

.head {
  background-color: darkslategray;
  padding: 20px;
}

.border3 {
    border: 1px solid black none;
    padding: 20px;
    width: 350px;
    background-color: white;
    float: left;
    text-align: right;
}

.border4 {
    border: 1px solid black none;
    padding: 20px;
    float: left;
    width: 65%;
    height: 894px;
    margin-bottom: 50px;
}

#p {
  background-color: lightgrey;
  padding: 20px;
  height: 320px;
}

h2 {
font-family: 'Times New Roman', Times, serif;
}

.wr {
float: left;
width: 245px;
height: 300px;
padding: 5px;

}

.ac {
float: left;
width: 30%;
height: 300px;
padding: 5px;
}

.skil {
float: left;
width: 40%;
height: 300px;
}

</style>
