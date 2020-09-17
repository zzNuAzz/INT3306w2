<div class="card mb-4">
    <img class="card-img-top" src="{{ include.postImg }}" alt="Card image cap">
    <div class="card-body">
        <h2 class="card-title">{{ include.postTitle }}</h2>
        <p class="card-text">{{ include.postBody }}</p>
    </div>
    <div class="card-footer text-muted">
        Posted on {{ include.postTime }}
    </div>
</div>
