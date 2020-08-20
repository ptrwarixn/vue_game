<template>
<div>
   <p>HP Player{{ randomNo(1,9)}}</p>
   {{ player[randomNo(1,9)-1].name}}
</div>
</template>

<script>
export default {
    data: function () {
        return {
player:[
{ name: 'Eevee',hp :'55'},
{ name: 'Espeon',hp :'65'},
{ name: 'Falreon',hp :'65'},
{ name: 'Glaceon',hp :'65'},
{ name: 'Jolteon',hp :'65'},
{ name: 'leafeon',hp :'65'},
{ name: 'Sylveon',hp :'95'},
{ name: 'Umbreon',hp :'95'},
{ name: 'Vaporeon',hp :'130'}
],
Monster:[
{ name: '',hp:''}
]


            
            
        };
    },
        methods:{
            
        }
        
    
}
</script>

<style>
    .button-apple{
    background-color: rgb(255, 252, 226);
    border: none;
    padding: 5px 5px 5px 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 8px;
    border: 0.5px solid #ebebeb;
    width : 60px;
}
.button-apple-font-dd{
    background-color: white;
    border: none;
    color: #646363;
    padding: 5px 5px 5px 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 8px;
    border: 0.5px solid #ebebeb;
    width : 60px;
}
button:hover#blue {
    color: blue;
}
button:hover#pink {
    color: rgb(255, 61, 174);
}
button:hover#yellow {
    color: yellow;
}
button:hover#orange {
    color: orange;
}
button:hover#violet {
    color: rgb(133, 0, 133);
}
button:hover#red {
    color:red;
}

</style>
