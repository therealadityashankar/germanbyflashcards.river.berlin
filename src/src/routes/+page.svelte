<script>
    import Progress from "$lib/progress.svelte"
</script>

<div class="flex justify-center items-center h-screen">
    <div class="card card-bordered p-8">
    <Progress/>
      <div class="flex flex-wrap justify-between items-center space-x-8">
        <div class="w-96">
          <div class="card card-bordered overflow-hidden">
            <div class="card-body">
              <p>
                Sogar meine Katze hat sich in das neue Sofa verliebt. 
            </div>
          </div>
        </div>
        <div class="w-48">
          <div class="card card-bordered">
            <div class="card-body">
              <button class="btn btn-primary mb-4">Again</button>
              <button class="btn btn-primary mb-4">Hard</button>
              <button class="btn btn-primary mb-4">Good</button>
              <button class="btn btn-primary">Easy</button>
            </div>
          </div>
        </div>
      </div>
    </div>
</div>
  