<template>
    <div class="d-flex p-4" style="background-color:#f4f4f4;">
        <a class="nav-link text-dark" href="#">Home /</a> 
        <a class="nav-link text-dark" href="#">Office Room /</a>
        <a class="nav-link text-dark" href="#">Details /</a>
        <a class="nav-link text-dark" href="#">Shipping /</a>
    </div> 
</template>

<script>
export default {
name: 'BreadcrumbComponent',
  props: {
    msg: String
  }
}

</script>

<style>

</style>