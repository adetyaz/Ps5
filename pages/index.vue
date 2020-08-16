<template>
  <div class="signup-body">
    <div class="head-content">
      <img
        src="../assets/images/PS5 Logo.png"
        alt="logo"
        class="head-content__logo"
      />
      <h3 class="head-content__date">4:00pm</h3>
    </div>
    <div class="signup">
      <p class="signup__sub-title">DualSense Connected</p>
      <h2 class="signup__title">Who is using the controller?</h2>
    </div>
    <div class="profiles">
      <div class="profiles__card">
        <img
          src="../assets/images/Icon.png"
          alt="plus icon"
          class="profiles__card-image"
        />
        <div class="profiles__card-text">
          <p class="profiles__card-title">Create User</p>
          <p class="profiles__card-description">
            Add a new user to this console
          </p>
        </div>
      </div>
      <div class="profiles__card">
        <img
          src="../assets/images/User1.png"
          alt="user image"
          class="profiles__card-image"
        />
        <div class="profiles__card-text">
          <p class="profiles__card-title">
            Jo-Accord
            <span
              ><img
                src="../assets/images/psplus.png"
                alt="ps plus"
                class="profile-icon"
            /></span>
          </p>
          <p class="profiles__card-description">
            Last online 3 hours ago
          </p>
        </div>
      </div>
      <div class="profiles__card">
        <img
          src="../assets/images/User2.png"
          alt="user image"
          class="profiles__card-image"
        />
        <div class="profiles__card-text">
          <p class="profiles__card-title">
            evebanigo
            <span
              ><img
                src="../assets/images/psplus.png"
                alt="ps plus"
                class="profile-icon"
            /></span>
          </p>
          <p class="profiles__card-description">
            Last online yesterday
          </p>
        </div>
      </div>
      <div class="profiles__card">
        <img
          src="../assets/images/shape.png"
          alt="users icon"
          class="profiles__card-image"
        />
        <div class="profiles__card-text">
          <p class="profiles__card-title">Play as Guest</p>
          <p class="profiles__card-description">
            Data will be deleted after you log out
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.signup-body {
  background: url('../assets/images/DualSense.png');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  background-color: $grey;
  padding: 3rem 5rem;
}

.head-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  &__logo {
    height: 0.8rem;
    margin: 1rem 2rem;
  }
  &__date {
    font-size: 1rem;
  }
}

.signup {
  margin-top: 3rem;
  &__title {
    font-size: 2.5rem;
    text-align: center;
    color: $black;
    margin: 1.5rem 0;
  }
  &__sub-title {
    position: relative;
    right: 9rem;
    font-size: 1.5rem;
    text-align: center;
    color: $black;
  }
}
.profiles {
  padding: 5rem 0;
  display: flex;
  align-items: center;
  justify-content: space-around;
  &__card {
    height: 20rem;
    width: 25rem;
    background-color: $white;
    box-shadow: 0 1rem 2rem rgba($black, 0.3);
    margin: 0 1rem;
    &-text {
      padding: 0 4rem;
    }
    &-image {
      height: 6rem;
      margin: 2.5rem 6rem;
    }
    &-title {
      font-size: 1.2rem;
      color: $black;
    }
    &-description {
      font-size: 0.8rem;
      color: $dark-grey;
      margin: 0.5rem 0;
    }
  }
}
.profile-icon {
  display: inline-block;
  height: 1.2rem;
  margin: 0 1rem;
}
</style>
