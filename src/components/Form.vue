<template>

<h2>Text Input</h2>
<input v-model="text" >{{ text }}

<h2>Checkbox</h2>
<input type="checkbox" id="checkbox" v-model="checked">
<label for="checkbox">checked:{{ checked }}</label>

</template>

<script>
export default {
    data() {
        return{
            text:'',
            checked:true,
            checkedNames:['Cheslyn'],
            picked:'one',
            multiSelected: ['A']
        }
    }
}
</script>


<template>
<h2>Multi checkbox</h2>
<input type="checkbox" id="Cheslyn" value="Cheslyn" v-model="checkedNames">
<label for="Cheslyn">Cheslyn</label>
<input type="checkbox" id="Luke" value="Luke" v-model="checkboxNames">
<label for="Luke">Luke</label>
<p>checked:
<pre>{{ checkedNames }}</pre>
</p>
</template>

<template>
<h2>Radio</h2>

<input type="radio" id="one" value="one" v-model="picked">
<label for="one">One</label>
<br>
<input type="radio" id="two" value="two" v-model="picked">
<label for="two">Two</label>
<br>
<span>Picked:{{ picked }}</span>
</template>

<template>
<h2>Multi Selected</h2>
<select v-model="multiSelected" multiple style="width:100px">
    <option>A</option>
    <option>B</option>
    <option>C</option>
    
</select>
<span>Selected: {{ multiSelected }}</span>
</template>