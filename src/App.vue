<template>
  <pdf src="example.pdf" :page="1" />
</template>

<script>
import pdf from 'pdfvuer'
  
export default {
  components: {
    pdf
  }
}
</script>

