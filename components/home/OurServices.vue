<template>
  <section>
    <v-container>
      <app-section-descriptor
        title="What is web3heaven?"
        heading="Introducing web3heaven"
        description="The groundbreaking platform poised to revolutionize the traditional payment system. Inefficiency, insecurity, and exorbitant costs have long plagued conventional payment methods. web3heaven seeks to disrupt this status quo by harnessing cutting-edge blockchain technologies, democratizing their benefits for all. With web3heaven, users can unlock the transformative power of decentralization, experiencing lightning-fast transaction speeds, enhanced security, heightened privacy, and significant cost savings. Join us on this pioneering journey as we reshape the future of payments, making it accessible, secure, and efficient for everyone."
        style="max-width: 64rem"
      />
      <div class="overview-features">
        <v-stack
          align="center"
          sm-align="start"
          gap="10rem"
          sm-gap="3rem"
          justify="space-evenly"
        >
          <div class="icon-container">
            <v-image class="serv-image" 
            path="images/speed.png" 
            alt="web3heaven Speed" />
          </div>
          <div class="overview-feature">
            <v-heading :level="2" class="overview-feature-title">
              Fast Transactions
            </v-heading>
            <v-heading :level="2" class="overview-feature-title">
            </v-heading>
            <div class="overview-feature-description">
              <v-text
                color="secondary"
                line-height="1.5"
                class="feature-description-text"
              >       
              web3heaven stands out as a fast blockchain network designed for everyday use. 
              The web3heaven speed enables fast transaction with confirmation time of only 5 seconds, making it ideal for swift and efficient daily transactions. 
              Whether you're making payments, conducting business, or engaging in other activities, web3heaven's rapid confirmation times ensure a seamless user experience. 
              With its focus on speed and usability, web3heaven empowers users with a blockchain network that can keep pace with the demands of modern-day transactions. 

              </v-text>
            </div>
          </div>
        </v-stack>
        <v-stack
          align="center"
          sm-align="start"
          gap="10rem"
          sm-gap="3rem"
          justify="space-evenly"
        >
          <div class="overview-feature">
            <div>
              <v-heading :level="2" class="overview-feature-title">
                Horizontal Scalability
             
              </v-heading>

            </div>
            
            <div class="overview-feature-description">
              <v-text
                color="secondary"
                line-height="1.5"
                class="feature-description-text"
              >        With web3heaven, say "Good-bye!" to network congestion and lengthy confirmation times. 
              web3heaven's custom BFT consensus mechanism achieve transaction finality within the same block. 
              By optimizing its blockchain protocol and transaction validation process,
              web3heaven minimizes delays and eliminates the need for extended waiting periods.
              Say goodbye to frustrating bottlenecks and experience the convenience of fast transaction confirmations on the web3heaven platform.

                    </v-text>
            </div>
          </div>
          <div class="icon-container">
            <v-image class="serv-image"
              path="images/scalability.png"
              alt="web3heaven Security"
            />
          </div>
        </v-stack>
        <v-stack
          align="center"
          sm-align="start"
          gap="10rem"
          sm-gap="3rem"
          justify="space-evenly"
        >
          <div class="icon-container">
            <v-image class="serv-image1"
              path="images/security.png"
              alt="web3heaven Scalability"
            />
          </div>
          <div class="overview-feature">
            <div>
              <v-heading :level="2" class="overview-feature-title">
                Unparallel Security
              </v-heading>
            </div>
            <div class="overview-feature-description">
              <v-text
                color="secondary"
                line-height="1.5"
                class="feature-description-text"
              >
              Blockchain security safeguards data integrity, confidentiality, and availability. 
              It utilizes decentralization, cryptography, and transparency to prevent tampering. 
              By distributing data and employing digital signatures, it ensures authenticity and prevents unauthorized modifications. 
              Regular audits and monitoring enhance trust in this highly secure technology for transactions and data storage.        
              </v-text>
              
            </div>
          </div>
        </v-stack>
        <v-stack
          align="center"
          sm-align="start"
          gap="10rem"
          sm-gap="3rem"
          justify="space-evenly"
        >
          <div class="overview-feature">
            <div>
              <v-heading :level="2" class="overview-feature-title">
              Environmentally Friendly             
             </v-heading>
            </div>
            
            <div class="overview-feature-description">
              <v-text
                color="secondary"
                line-height="1.5"
                class="feature-description-text"
              >
              The web3heaven blockchain utilizes Proof-of-Stake (PoS), an energy-efficient and eco-friendly approach. 
              Unlike energy-consuming Proof-of-Work (PoW), PoS relies on stakeholder participation, eliminating resource-intensive mining. 
              web3heaven's innovative nPoS consensus ensures efficient block verification while prioritizing sustainability.
              </v-text>
            </div>
          </div>
          <div class="icon-container">
            <v-image class="serv-image"
              path="images/eco5.png"
              alt="web3heaven Eco"
            />
          </div>
        </v-stack>
        
      </div>
    </v-container>
  </section>
</template>

<script>
export default {
  name: 'Features',
}
</script>

<style lang="css" scoped>
@import url('../lib/media-query-helper.css');

section {
  padding-bottom: 6rem;

  @media (--viewport-small) {
    padding-bottom: 3rem;
  }
}

.overview-description {
  max-width: 52ch;
  font-size: 1.25rem;

  @media (--viewport-small) {
    font-size: 1rem;
  }
}

.overview-feature {
  max-width: 40rem;
  text-align: left;
}

.overview-features > * {
  margin-top: 6rem;

  @media (--viewport-small) {
    margin-top: 3rem;
  }
}

.overview-feature-title {
  margin: 0;
  font-size: 2.25rem;
  line-height: 1.5;

  @media (--viewport-small) {
    font-size: 1.25rem;
  }
}

.overview-feature-description {
  margin-top: 1.25rem;
}

.feature-description-text {
  font-size: 1.375rem;

  @media (--viewport-small) {
    font-size: 0.875rem;
  }
}
.serv-image{
  max-width: 20vw;
}
.serv-image1{
  max-width: 22vw;
}
.icon-container {
  position: relative;
  overflow: visible;
}

/* .icon-container::before {
  content: '';
  position: absolute;
  top: -40%;
  left: -40%;
  right: -40%;
  bottom: -40%;
  z-index: -1;
  background: radial-gradient(
    45% 40% at 50% 50%,
    rgba(112, 239, 207, 0.3) 0%,
    rgba(0, 0, 0, 0) 100%
  );
  filter: blur(5px);
} */

.icon-container:nth-child(2)::before {
  background: radial-gradient(
    45% 40% at 50% 50%,
    rgba(112, 239, 207, 0.3) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.icon-container > * {
  @media (--viewport-medium) {
    width: 10rem;
    margin-top: 1rem;
  }

  @media (--viewport-small) {
    width: 6rem;
    margin-top: 0.5rem;
  }
}
</style>
