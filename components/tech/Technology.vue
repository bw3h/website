<template>
  <section>
    <!-- <v-container class="technology-container">
      <v-container>
      <v-stack>
        <app-section-descriptor
          title="Roadmap"
          heading="Luminet Roadmap"
          description="At Luminet, our relentless pursuit is to establish the forefront of payment systems. Discover our remarkable achievements and ongoing endeavors below. Inspired? Join us in shaping the future! Together, we can make Luminet the epitome of advancement in the realm of payments."
          style="max-width: 58rem"
        />
      </v-stack>
      <div class="roadmap-container">
      <v-image
        path="images/roadmap-desktop.png"
        class="tablet-remove mobile-remove roadmap-desktop"
      />
      <div class="laptop-remove position-relative" style="text-align: center">
        <v-image path="images/roadmap-mobile-bg.png" class="roadmap-mobile" />
      </div>
      </div>
    </v-container> -->



<!-- 
      <v-stack md-direction="column" justify="space-between" align="center">
        <v-stack direction="column" class="technology-hero-section">
          <v-heading :level="1">
            A Comprehensive Stack To Help Developers Build Secure and Privacy
            Preserving Apps
          </v-heading>
          <app-section-descriptor
            description="Decentralised storage, identity, access management, and KMS to help developers build secure and privacy‑preserving apps."
            class="technology-hero-description"
          />
        </v-stack>
        <div class="illustration-container hero-image-container">
          <v-image path="images/tech-illustration.png" class="hero-image" />
        </div>
      </v-stack> -->

      <!-- <v-stack justify="space-between" align="center">
        <div class="illustration-container tech-illustration storage">
          <v-image
            path="images/decentralised-storage.svg"
            class="tablet-remove mobile-remove"
          />
        </div>
        <v-stack direction="column" md-align="center" class="tech-stack">
          <app-section-descriptor
            heading="Decentralised Storage"
            description="Storage nodes store only a piece of an encrypted file, ensuring data security at rest. No snooping by anyone!"
            class="tech-stack-description"
          />
          <div class="illustration-container tech-illustration storage">
            <v-image
              path="images/decentralised-storage.svg"
              class="laptop-remove"
            />
          </div>
          <v-stack
            wrap
            class="features-list"
            md-direction="column"
            md-justify="center"
          >
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Files uploaded to Luminet are erasure coded into shards.
              </v-text>
            </v-chip>
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Each shard is stored on a unique Luminet storage node.
              </v-text>
            </v-chip>
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Only a subset of these shards are required to retrieve the file.
              </v-text>
            </v-chip>
          </v-stack>
        </v-stack>
      </v-stack> -->

      <!-- <v-stack justify="space-between" align="center">
        <v-stack direction="column" md-align="center" class="tech-stack">
          <app-section-descriptor
            heading="End to End Encryption"
            description="No one except intended recipients can access files."
            class="tech-stack-description"
          />
          <div class="illustration-container tech-illustration encryption">
            <v-image path="images/e2e-encryption.svg" class="laptop-remove" />
          </div>
          <v-stack
            wrap
            class="features-list"
            md-direction="column"
            md-justify="center"
          >
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                All files are encrypted by the client even before they hit the
                network.
              </v-text>
            </v-chip>
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Symmetric key encryption of files and asymmetric encryption of
                symmetric keys.
              </v-text>
            </v-chip>
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Proxy re-encryption (PRE) to seamlessly share /re share files.
              </v-text>
            </v-chip>
          </v-stack>
        </v-stack>
        <div class="illustration-container tech-illustration encryption">
          <v-image
            path="images/e2e-encryption.svg"
            class="tablet-remove mobile-remove"
          />
        </div>
      </v-stack> -->

   <!-- <v-stack justify="space-between" align="center">
        <div class="illustration-container tech-illustration key-management">
          <v-image
            path="images/key-management.svg"
            class="tablet-remove mobile-remove"
          />
        </div>
        <v-stack direction="column" md-align="center" class="tech-stack">
          <app-section-descriptor
            heading="Non-Custodial Key Management"
            description="Users need not store or manage keys."
            class="tech-stack-description"
          />
          <div class="illustration-container tech-illustration key-management">
            <v-image path="images/key-management.svg" class="laptop-remove" />
          </div>
          <v-stack
            wrap
            class="features-list"
            md-direction="column"
            md-justify="center"
          >
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Secure and distributed key generation and storage.
              </v-text>
            </v-chip>
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Verifiable logs of key generation and storage steps. Fully
                customisable signup/login.
              </v-text>
            </v-chip>
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Password-less sign up/login with any popular auth. mechanism
                (Gmail, Facebook, etc.).
              </v-text>
            </v-chip>
          </v-stack>
        </v-stack>
      </v-stack> -->
<!-- 
    <v-stack justify="space-between" align="center">
        <v-stack direction="column" md-align="center" class="tech-stack">
          <app-section-descriptor
            heading="Decentralised IAM"
            description="Your users truly own and control sharing access to their data."
            class="tech-stack-description"
          />
          <div class="illustration-container tech-illustration iam">
            <v-image
              path="images/decentralised-iam.svg"
              class="laptop-remove"
            />
          </div>
          <v-stack
            wrap
            md-direction="column"
            class="features-list"
            md-justify="center"
          >
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Every file uploaded to Luminet is assigned a DID, as per the W3C
                DID spec(link).
              </v-text>
            </v-chip>
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                DID points to document stored on the public Luminet blockchain
                for trust-less verification.
              </v-text>
            </v-chip>
            <v-chip>
              <v-text color="secondary" line-height="1.5rem" size="1.125rem">
                Access control list maintained in the DID document can only be
                updated by the file owner/uploader.
              </v-text>
            </v-chip>
          </v-stack>
        </v-stack>
        <div class="illustration-container tech-illustration iam">
          <v-image
            path="images/decentralised-iam.svg"
            class="tablet-remove mobile-remove"
          />
        </div>
      </v-stack> -->
    <!-- </v-container> -->
  </section>
</template>

<script>
export default {
  name: 'Technology',
}
</script>

<style lang="postcss" scoped>
@import url('../lib/media-query-helper.css');

section {
  @media (--viewport-small) {
    margin-top: 0 !important;
  }
}

.illustration-container {
  position: relative;
}

.hero-image-container::before {
  content: '';
  position: absolute;
  inset: -20% -50% -50%;
  z-index: -1;
  background: radial-gradient(
    50% 40% at 50% 55%,
    rgba(248, 81, 142, 0.2) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.tech-illustration::before {
  content: '';
  position: absolute;
  inset: -50%;
  z-index: -1;
}

.tech-illustration.storage::before {
  z-index: 1;
  background: radial-gradient(
    50% 50% at 50%,
    rgba(33, 130, 118, 0.2) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.tech-illustration.encryption::before {
  background: radial-gradient(
    50% 50% at 50% 50%,
    rgba(255, 233, 206, 0.2) 0%,
    rgba(0, 0, 0, 0) 100%
  );
  filter: blur(40px);
}

.tech-illustration.key-management::before {
  background: radial-gradient(
    50% 50% at 50% 50%,
    rgba(248, 81, 142, 0.2) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.tech-illustration.iam::before {
  background: radial-gradient(
    50% 50% at 50%,
    rgba(33, 130, 118, 0.2) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.technology-hero-section {
  max-width: 48rem;
}

.technology-hero-description {
  max-width: 38rem;
}

.hero-image {
  min-width: 28rem;
  margin-top: 3rem;
  max-width: 32rem;

  @media (--viewport-small) {
    min-width: auto;
    max-width: 12rem;
  }
}

.tech-stack {
  width: 100%;
  max-width: 48rem;
}

.tech-stack > * {
  margin-top: 1rem;
}

.features-list {
  margin: 0 0 0 -1.5rem;
}

.features-list > * {
  margin: 1.5rem 0 0 1.5rem;
}

.technology-container > *:not(:first-child) {
  margin-top: 6rem;

  @media (--viewport-medium) {
    margin-top: 4rem;
  }

  @media (--viewport-small) {
    margin-top: 2rem;
  }
}

.tech-stack-description {
  max-width: 30rem;
}
</style>
