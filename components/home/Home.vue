<template>
  <div class="">
    <div class="home-page">
      <div class="title">
        <h2>
          Chương trình truyền hình, phim không giới hạn và nhiều nội dung khác.
        </h2>
        <h5>Xem ở mọi nơi. Hủy bất kỳ lúc nào.</h5>
        <p>
          Bạn đã sẵn sàng xem chưa? Nhập email để tạo hoặc kích hoạt lại tư cách
          thành viên của bạn.
        </p>
      </div>

      <div class="email-form">
        <input type="text" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home-page",
  data() {
    return {};
  },
};
</script>

<style lang="css" scoped>
.home-page {
  height: 803px;
  z-index: 1;
  position: relative;
  justify-content: center;
  background-image: linear-gradient(rgba(0, 0, 0, 0.527), rgba(0, 0, 0, 0.5)),
    url(https://assets.nflxext.com/ffe/siteui/vlv3/ac824598-245b-4828-b14f-5cff9074f4d0/2dc90a8e-4441-4703-8b73-1ca831fb0733/VN-vi-20220822-popsignuptwoweeks-perspective_alpha_website_large.jpg);
}
/* .xxx {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  z-index: -1;
  background-image: linear-gradient(0deg, #041129, rgba(3, 14, 35, 0.28));
} */

.home-page > .title {
  width: 45%;
  padding-top: 300px;
  margin: auto;
  text-align: center;
  color: #fff;
}
.home-page > .title > h2 {
  font-size: xxx-large;
  font-weight: 700;
}
.home-page > .title > h5 {
  font-size: large;
  font-weight: 600;
}
</style>
