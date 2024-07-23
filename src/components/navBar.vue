<template>
<nav class="navbar navbar-expand-lg  bg-black p-0 ">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
       <img class="img-fluid " style="width: 90px; height:60px" src="@/assets/logo.png" alt="logo">
    </a>
    <button class="navbar-toggler text-white border border-2 fs-1 rounded-2" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span ><i class="bi bi-list  "></i> </span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item ">
          <a class="nav-link text-white" href="#">About</a>
        </li>
        <li class="nav-item ">
          <a class="nav-link text-white" href="#">Service</a>
        </li><li class="nav-item ">
          <a class="nav-link text-white" href="#">Contact</a>
        </li>
        
      </ul>
      <form class="d-flex mb-4 mb-lg-0 " role="search">
        <input class="form-control rounded-0 " type="search" placeholder="Search.." aria-label="Search">
        <button class="btn bg-danger text-white border rounded-0 me-5 searchBtn"  type="submit"><i class="bi bi-search "></i></button>
      </form>
    </div>
  </div>
</nav>
</template>

<!-- script section -->
<script>

export default{
    name:"navBar",

}
</script>

<!-- style section -->
<style scoped>
.customBtn{
  color: white;
}
.searchBtn:hover
{
  background-color: black ;
  color: red;
}
</style>