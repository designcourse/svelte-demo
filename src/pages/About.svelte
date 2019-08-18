<script>
  export let router = {};

  // Those contains useful information about current route status
  router.path; // /test
  router.route; // Route Object
  router.params; // /about/bill/123/kansas { who: 'bill', where: 'kansas' }
</script>

<h1>About me</h1>

<p>This is my router path: {router.path}</p>