<template>
  <v-container>
    <h2 class="header">About Us</h2>
    <br />
    <v-divider></v-divider>
    <br />
    <v-row>
      <v-col cols="12" md="4">
        <v-img
          class="image"
          src="img/The_Boys.JPG"
          alt="Jack, Reid, and Bayrd"
          title="Jack, Reid, and Bayrd"
          max-width="12em"
        ></v-img>
      </v-col>
      <v-spacer></v-spacer>
      <v-col cols="12" md="6">
        <p>
          Kids4KidsTech! is a not-for-profit organization established by three brothers, Jack (14),
          Reid (12), and Bayrd (10).
        </p>
        <p>
          During the Coronavirus epidemic and the transition to virtual learning, the boys
          experienced firsthand how vital technology was to their education.
        </p>
      </v-col>
    </v-row>
    <br />
    <v-divider></v-divider>
    <br />
    <v-row>
      <v-col>
        <h4 class="header">OUR DISCOVERY</h4>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" md="6">
        <p>
          When the boys visited their mother Jennifer’s interior design showroom in the South
          Seattle neighborhood of Georgetown, they were struck by the stark juxtaposition of the
          luxury inside the warehouse verus the view of the street. Up and down both sides, they
          observed wooden boards, tarps, and tents of people experiencing homelessness and saw young
          people among the group gathered outside.
        </p>
      </v-col>
      <v-spacer></v-spacer>
      <v-col cols="12" md="4">
        <v-img
          class="image"
          src="img/Jen.JPG"
          alt="Jennifer West"
          title="Jennifer West"
          max-width="12em"
        ></v-img>
      </v-col>
    </v-row>
    <br />
    <v-divider></v-divider>
    <br />
    <v-row>
      <v-col>
        <h4 class="header">THE SITUATION</h4>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" md="4">
        <v-row>
          <v-col cols="12" sm="6">
            <v-img
              class="image"
              src="img/Shanty1.JPG"
              alt="Shanty"
              title="Shanty"
              max-width="15em"
            ></v-img>
          </v-col>
          <v-col cols="12" sm="6">
            <v-img
              class="image"
              src="img/Shanty2.JPG"
              alt="Shanty"
              title="Shanty"
              max-width="15em"
            ></v-img>
          </v-col>
        </v-row>
      </v-col>
      <v-spacer></v-spacer>
      <v-col cols="12" md="6">
        <p>
          The brothers were deeply troubled by the situation, and wanted to do something to help.
        </p>
        <v-row>
          <v-col cols="12" md="6">
            <v-card>
              <v-card-text>
                It seemed as if there was a huge issue that was being overlooked and needed to be
                addressed.
                <br />
                <span class="quote-name">-Jack</span>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card>
              <v-card-text>
                It will feel good to truly make a difference in the community.
                <br />
                <span class="quote-name">-Reid</span>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
        <p>
          Together, the three boys were inspired to take action, raising money to support remote
          learning for those students unable to access reliable technological resources.
        </p>
        <p>
          They studied the homeless crisis in Seattle and learned that, according to the
          Point-in-Time Count for Seattle/King County, there were 11,751 individuals experiencing
          homelessness in January 2020, a 5% increase from the previous year’s count.
        </p>
      </v-col>
    </v-row>
    <br />
    <v-divider></v-divider>
    <br />
    <v-row>
      <v-col>
        <h4 class="header">HOW TECHNOLOGY CAN HELP</h4>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <p>
          While some may think of technology as a luxury for people who cannot afford to buy food,
          in fact, access to technology is critical to their ability to find resources and improve
          their situation. Access to the internet can empower individuals with access to
          information, healthcare, food and community. Now, it is especially important for students
          who are trying to go to school remotely and don’t want to fall behind in school.
        </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<style lang="scss" scoped>
// * {
//   border: 1px solid red;
// }

h4 {
  text-decoration: underline;
}

.header {
  text-align: center;
}

.image {
  margin: auto;
}

.quote-name {
  position: absolute;
  top: 70%;
  right: 5%;
}
</style>
