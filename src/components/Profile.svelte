<script>
  import profilePicture from "../assets/user.webp";
  export let nickname;
  export let name;
</script>

<div class="profile">
  <div class="profile-content">
    <div class="profile-avatar">
      <img src={profilePicture} alt="profile-img" />
    </div>
    <div class="profile-info">
      <h2>{nickname}</h2>
      <span>{name}</span>
    </div>
  </div>
</div>

<style>
  .profile-content {
    display: flex;
    align-items: center;
  }
  .profile-avatar img {
    max-width: 55px;
    max-height: 55px;
    border-radius: 50%;
  }
  .profile-info {
    margin: 0 0 0 0.5em;
  }
  .profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>
