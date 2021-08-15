<template>
  <div>
    <h1>Bienvenue sur mon site</h1>
    <div class="row">
      <div class="col-sm-4">
        <Card
          title="Bike"
          content="Ma passion... la moto"
          image="HD.jpeg"
          href="/description/bike"
        />
      </div>

      <div class="col-sm-4">
        <Card
          title="Dev"
          content="Mon boulot le dev web"
          image="dev.jpeg"
          href="/description/dev"
        />
      </div>

      <div class="col-sm-4">
        <Card
          title="Familly"
          content="Ma plus belle reussite"
          image="familly.jpeg"
          href="/description/familly"
        />
      </div>
    </div>
  </div>
</template>

<script>
import Card from "@/components/Card";
export default {
  components: {
    Card
  }
};
</script>

<style lang="scss" scoped></style>
