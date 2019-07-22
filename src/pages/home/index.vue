<template>
  <div>
    <div class="search">
      <div class="searchBar">
        <icon type="search"></icon>
        <span>搜索</span>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  }
};
</script>
<style lang="" scope>
div .search {
  background-color: #eb4450;
  height: 35px;
  padding: 10px;
}
div .search .searchBar {
  background-color: #fff;
  width: 355px;
  height: 30px;
  text-align: center;
  padding: 3px;
  box-sizing: border-box;
}
div .search .searchBar icon {
  vertical-align: middle;
}
div .search .searchBar span {
  color: #666;
  font-size: 14px;
  margin-left: 5px;
}
</style>
