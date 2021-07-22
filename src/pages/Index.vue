<template>
  <Layout>
          <div class="row">
            <div class="column">
                <br>
                <center>
                    <img id="circle" src="https://scontent.fhdy3-1.fna.fbcdn.net/v/t1.6435-9/92099342_2820290681420108_2695528926737858560_n.jpg?_nc_cat=106&ccb=1-3&_nc_sid=174925&_nc_eui2=AeEB8ySSTAlFv_7JWF46LYJT-qmiTepCW5v6qaJN6kJbm-NLXpc9DIz14LuAm5MYjMeP-rIyD6cu_zYUzONeISti&_nc_ohc=sVQdW8LnK9IAX-23YpP&_nc_ht=scontent.fhdy3-1.fna&oh=bfab34089011aac67159ce1a108b7765&oe=60FE6AFA" alt="">
                    <h1 id="name">WANISH SENGKHIM</h1>
                    <h2 id="position">Full Stack Developer</h2>
                    <br>
                    <hr>
                    <br>
                    <h1 id="skill" style="color: aquamarine; line-height: ;">Skills</h1>
                </center>
                <div class="skills">
                    <table>
                        <tr>
                            <th style="padding: 20px;">
                                <td>
                                    <div class="color" style="color: gold;">FRONT END :</div>
                                    <p style="color: white;">C, HTML, CSS, Javascript,
                                    <br>Java, React, Python</p>
                                    <div class="color" style="color: gold;">BACK END :</div>
                                    <p style="color: white;">Node.Js</p>
                                    <div class="color" style="color: gold;">DATABASE :</div>
                                    <p style="color: white;">Firebase, MongoDB, Neo4j</p>
                                </td>
                                <td style="padding: 50px; line-height: auto;">
                                    <div class="color" style="color: gold;">DEV OPS :</div>
                                    <p style="color: white;">VMWare, Docker</p>
                                    <div class="color" style="color: gold;">MOBILE APP :</div>
                                    <p style="color: white;">React-Native, Flutter(Dart)</p>
                                    <div class="color" style="color: gold;">Graphic :</div>
                                    <p style="color: white;">Adobe Photoshop, Premier Pro</p>
                                </td>
                            </th>
                        </tr>
                        
                    </table>

                    
                </div>
            
                </div>
                <hr>
                <br>
            
            <div class="column">
                <center>
                <h1 id="education" style="color: aquamarine;">EDUCATION</h1>
                <table>
                    <tr>
                        <th rowspan="1" style="padding: 20px; color: gold;"><h2>2012-2017</h2></th>
                        
                        <td style="padding: 10px; color: white;">Mahavajiravudh Songkhla School
                            <br>High School, Science - Math</td>
                      </tr>
                      <tr>
                        <th rowspan="1" style="padding: 20px; color: gold;"><h2>2017-NOW</h2></th>
                        <td style="padding: 10px; color: white;">Prince of Sonkla University
                            <br>Faculty of Engineering, Computer of Enginerring
                        </td>
                      </tr>
                </table>
                <br>
                <hr>
                <h1 id="education" style="color: aquamarine;">EXPERIENCE</h1>
                <table>
                    <tr>
                        <th rowspan="1" style="padding: 20px; color: gold;"><h2>2019</h2></th>
                        
                        <td style="padding: 10px; color: white;">Completed the Comptia Cloud Essential Certified
                        <br>@ Prince of Songkla University Phuket campus</td>  
                    </tr>
                    <tr>
                        <th rowspan="1" style="padding: 20px; color: gold;"><h2>2019</h2></th>
                        
                        <td style="padding: 10px; color: white;">Join 12th Robot design Camp 2019
                        <br>Qualified for the national level
                        <br>@ Chulalongkorn University</td>  
                    </tr>
                    <tr>
                        <th rowspan="1" style="padding: 20px; color: gold;"><h2>2019</h2></th>
                        
                        <td style="padding: 10px; color: white;">Organizer of eCamp : Next Gen 2019
                        <br>@ Prince of Songkla University</td>  
                    </tr>
                </table>
            </center>
            </div>
          </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style>
@import url(https://fonts.googleapis.com/css?family=Six+Caps);
html * {
  box-sizing: border-box;
}

body {
  font-size: 18px;
  padding: 10px;
  background: #333333;
  color: #ffffff;
  text-align: center;
  height: 100vh;
  margin: 0;
  display: -webkit-box;
  display: flex;
  -webkit-box-align: center;
  align-items: center;
  height: auto;
}

#circle {
  width: 15vw;
  border-radius: 50%;
}

.container {
  width: 100%;
}
.skills{
  float: center;
}
</style>
