<template>
  <div class="row">
    <div class="col-md-4 d-flex align-items-stretch">
      <div class="box">
        <div class="our-services settings">
          <div class="icon">
            <img src="https://i.imgur.com/6NKPrhO.png" />
          </div>
          <h4>Design & Drawing</h4>
          <p class="text-justify">
            Our highly qualified & well-experienced engineers are able to Design
            & Commission the system to meet the requirements of NFPA or Others
            International & Local Authorities.
          </p>
        </div>
      </div>
    </div>
    <div class="col-md-4 d-flex align-items-stretch">
      <div class="box">
        <div class="our-services speedup">
          <div class="icon">
            <img src="https://i.imgur.com/KMbnpFF.png" />
          </div>
          <h4>Fabrication</h4>
          <p class="text-justify">
            Fabrication engineers make, install and repair metal products such
            as vents, handrails, boilers, aircraft and boat parts, or beams and
            girders for construction projects.
          </p>
        </div>
      </div>
    </div>
    <div class="col-md-4 d-flex align-items-stretch">
      <div class="box">
        <div class="our-services privacy">
          <div class="icon">
            <img src="https://i.imgur.com/AgyneKA.png" />
          </div>
          <h4>Installation</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
        </div>
      </div>
    </div>
    <div class="col-md-4 d-flex align-items-stretch">
      <div class="box">
        <div class="our-services backups">
          <div class="icon">
            <img src="https://i.imgur.com/vdH9LKi.png" />
          </div>
          <h4></h4>
          <h4>Testing & Commissioning</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
        </div>
      </div>
    </div>
    <div class="col-md-4 d-flex align-items-stretch">
      <div class="box">
        <div class="our-services ssl">
          <div class="icon">
            <img src="https://i.imgur.com/v6OnUqu.png" />
          </div>
          <h4>Civil & Architect</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
        </div>
      </div>
    </div>
    <div class="col-md-4 d-flex align-items-stretch">
      <div class="box">
        <div class="our-services database">
          <div class="icon">
            <img src="https://i.imgur.com/VzjZw9M.png" />
          </div>
          <h4>Maintenance Services</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'OurServiceIndex',
}
</script>

<style scoped>
.box {
  position: relative;
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
}
.our-services {
  margin-top: 75px;
  padding-bottom: 30px;
  padding: 0 60px;
  min-height: 198px;
  text-align: center;
  border-radius: 10px;
  background-color: #fff;
  transition: all 0.4s ease-in-out;
  box-shadow: 0 0 25px 0 rgba(20, 27, 202, 0.17);
}

.our-services .icon {
  margin-bottom: -21px;
  transform: translateY(-50%);
  text-align: center;
}

.our-services:hover h4,
.our-services:hover p {
  color: #fff;
}

.speedup:hover {
  box-shadow: 0 0 25px 0 rgba(20, 27, 201, 0.05);
  cursor: pointer;
  background-image: linear-gradient(-45deg, #fb0054 0%, #f55b2a 100%);
}

.settings:hover {
  box-shadow: 0 0 25px 0 rgba(20, 27, 201, 0.05);
  cursor: pointer;
  background-image: linear-gradient(-45deg, #34b5bf 0%, #210c59 100%);
}

.privacy:hover {
  box-shadow: 0 0 25px 0 rgba(20, 27, 201, 0.05);
  cursor: pointer;
  background-image: linear-gradient(-45deg, #3615e7 0%, #44a2f6 100%);
}

.backups:hover {
  box-shadow: 0 0 25px 0 rgba(20, 27, 201, 0.05);
  cursor: pointer;
  background-image: linear-gradient(-45deg, #fc6a0e 0%, #fdb642 100%);
}

.ssl:hover {
  box-shadow: 0 0 25px 0 rgba(20, 27, 201, 0.05);
  cursor: pointer;
  background-image: linear-gradient(-45deg, #8d40fb 0%, #5a57fb 100%);
}

.database:hover {
  box-shadow: 0 0 25px 0 rgba(20, 27, 201, 0.05);
  cursor: pointer;
  background-image: linear-gradient(-45deg, #27b88d 0%, #22dd73 100%);
}
</style>
