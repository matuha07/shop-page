<template>
<div class="search text-center">
    <div class="input-group input-group-sm mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default">Поиск</span>
        <input type="text" class="form-control" aria-label="Sizing example input"
            aria-describedby="inputGroup-sizing-sm">
    </div>
    <div class="dropdown">
        <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
            Фильтр
        </button>
        <ul class="dropdown-menu mb-3">
            <li><a class="dropdown-item" href="#">1</a></li>
            <li><a class="dropdown-item" href="#">2</a></li>
            <li><a class="dropdown-item" href="#">3</a></li>
        </ul>
    </div>
</div>
</template>