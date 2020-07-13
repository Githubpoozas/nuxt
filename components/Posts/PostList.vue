<template>
  <section class="posts-list">
    <PostPreview
      id="1"
      thumbnail="https://lh3.googleusercontent.com/proxy/9clw8gEZzD3ZQuBLE4KAiR9VaJfIzqa872jT1nUr4rbcOc2ZMzbfvGH9sIEq_1Oxxv6rDpMqAFKnVFj3vlGBOpA-a-od"
      title="Hello there!"
      previewText="This is my first post!"
    />
    <PostPreview
      id="2"
      thumbnail="https://lh3.googleusercontent.com/proxy/uLVFomtXCeMRKezZfxTweGIjM6ecZvPz-EpjXSXdq23ayK3vZLT7xk-g10mkuAM9GYZMzRCxRnKp1iatVKZbWB3gv6FM9J3ZO03UUOs8MhK-fLvEB_ii4yjnhp8qH2GVQjEzXCceCD0j1dxZ7XmjzGHxcRLgslvZ2oXNEg"
      title="Hello there! second time"
      previewText="This is my second post!"
    />
    <PostPreview
      id="3"
      thumbnail="https://lh3.googleusercontent.com/proxy/15ZzR000O9LbpouAgqoKK_8olaC4EmZNn53zWS8XA-SWGmBdqglt7FQba3Sx696Bb_QsjF_Uw27Sneynch3obtmhLjyHiqcFSx6-IU5ziWjqqMCVOK1O"
      title="Hello there! third time"
      previewText="This is my third post!"
    />
  </section>
</template>

<script>
import PostPreview from "@/components/Posts/PostPreview";

export default {
  components: {
    PostPreview
  }
};
</script>

<style scoped>
.posts-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
