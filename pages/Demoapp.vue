<template>
  <div>
    <h1> Demoapp has a prop {{ x }} </h1>
  </div>
</template>

<Script>

  export default  {
    props: {
      x: {
        type: String,
        required: true,
        default: "hello nuxt",
      },
    }
  }

</Script>
