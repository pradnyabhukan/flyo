<template>
  <div class="feedback-card">
    <div class="content">
      <p class="text">{{ content }}</p>
    </div>
    <div class="team-member">
      <div class="image">
        <img class="img" :src="img" alt="" />
      </div>
      <div class="member">
        <p class="name">{{ name }}</p>
        <p class="occupation">{{ occupation }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FeedbackCard',
  props: {
    content: {
      type: String,
      required: true,
    },
    img: {
      type: String,
      required: true,
    },
    name: {
      type: String,
      required: true,
    },
    occupation: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
  .feedback-card {
    padding: 2%;
    background-color: #202A3C;
  }
  .text {
    font-family: var(--font-body);
    font-size: 14px;
    font-weight: 400;
  }
  .team-member {
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }
  .img {
    height: 24px;
    width: 24px;
    border-radius: 50%;
  }
  .member .name {
    font-family: var(--font-heading);
    font-size: 10px;
    font-weight: 700;
    margin: 0;
  }
  .member .occupation {
    font-family: var(--font-body);
    font-size: 7px;
    font-weight: 400;
    margin: 0;
  }
  @media (max-width: 420px) {
    .feedback-card {
      padding: 5%;
    }
  }
</style>
