<template>
  <tr>
    <td><img :src="product_data.image" alt="22bet Wettsteuer"><a href="#">{{product_data.name}}</a></td>
    <td>{{product_data.bonus}}</td>
    <td>{{product_data.mindestquote}}</td>
    <td>{{product_data.bewertung}}</td>
    <td><a href="#" class="btn-buy">JETZT WETTEN</a></td>
  </tr>
</template>

<script>
export default {
  name: 'catalog-item',
  props: {
    product_data: {
      type: Object,
      default () {
        return {}
      }
    }
  }
}
</script>

<style scoped lang="scss">
  tr:nth-of-type(2n+1){
    background-color: #fff;
  }
  tr:nth-of-type(2n){
    background-color: #f9f9f9;
  }
  tr:hover {
    background-color: #f3f3f3;
  }
  td {
    vertical-align: middle;
    padding: 8px;
    color: #424242;
    img {
      max-width: 120px;
      height: auto;
    }
    a {
      color: #4080ff;
      display: flex;
      justify-content: center;
      font-size: 12px;
      &:hover {
        color: #ebaa3d;
      }
    }
    .btn-buy {
      font-size: 14px;
      color: #fff;
      background-color: #f3961d;
      border-color: #f3961d;
      display: inline-block;
      padding: 6px 12px;
      border-radius: 4px;
      &:hover {
        background-color: #f4a033;
        border-color: #f4a033;
        color: #fff;
        text-decoration: none;
      }
    }
  }
  @media all and (max-width: 768px) {
    td:nth-of-type(3), td:nth-of-type(4), th:nth-of-type(3), th:nth-of-type(4) {
      display: none;
    }
    td {
      img {
        max-width: 80px;
      }
      .btn-buy {
        font-size: 11px;
      }
    }
  }
  @media all and (max-width: 360px) {
    td {
      position: relative;
      img {
        max-width: 70px;
      }
      a {
        font-size: 10px;
      }
      .btn-buy {
        font-size: 9px;
      }
    }
    td, th {
      font-size: 12px;
    }
  }
</style>
