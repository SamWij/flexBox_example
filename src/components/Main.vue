<template>
    <div class="page-wrap">
        <div class="flex-container row-1">
        <div class="flex-item">1</div>
        <div class="flex-item">2</div>
        <div class="flex-item">3</div>
        <div class="flex-item">4</div>
        <div class="flex-item">5</div>
        </div>
        <div class="flex-container row-2">
        <div class="flex-item">1</div>
        <div class="flex-item">2</div>
        <div class="flex-item">3</div>
        <div class="flex-item">4</div>
        <div class="flex-item">5</div>
        </div>
        <div class="flex-container row-3">
        <div class="flex-item">1</div>
        <div class="flex-item">2</div>
        <div class="flex-item">3</div>
        <div class="flex-item">4</div>
        <div class="flex-item">5</div>
        </div>
        <div class="flex-container row-4">
        <div class="flex-item">1</div>
        <div class="flex-item">2</div>
        <div class="flex-item">3</div>
        <div class="flex-item">4</div>
        <div class="flex-item">5</div>
        </div>
        <div class="flex-container row-5">
        <div class="flex-item">1</div>
        <div class="flex-item">2</div>
        <div class="flex-item">3</div>
        <div class="flex-item">4</div>
        <div class="flex-item">5</div>
        </div>
    </div>
</template>

<style>
.page-wrap {
  height: 620px;
  /* equal to footer height */
  margin-bottom: -100px; 
}
.page-wrap:after {
  display: block;
  height: 100px; 
}

.flex-container {
    padding: 0;
    margin: 0;
    list-style: none;
    display: -webkit-box;
    display: -moz-box;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-flow: row;
    justify-content: space-around;
   
    line-height:30px;
}
.flex-item {
    background: tomato;
    margin: 5px;
    color: white;
    font-weight: bold;
    font-size: 1.5em;
    text-align: center;
    flex: 1 0 auto;
    height:auto;
}
.flex-item:before {
    content:'';
    float:left;
    padding-top:100%;
    text-align: center;
}
</style>
