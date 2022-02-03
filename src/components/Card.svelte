<script>
  export let className = "";
</script>

<div class="card {className}">
  
    <slot></slot>
  </div>
  
  <style>
    .card {
      background-color: #fff;
      color: #333;
      border-radius: 15px;
      padding: 40px 50px;
      margin: 20px 0;
      position: relative;
    }
    .card-list:hover {
      box-shadow: rgba(0, 0, 0, 0.25) 0px 14px 28px, rgba(0, 0, 0, 0.22) 0px 10px 10px;
      transform: scale(1.01);
    }
  </style>