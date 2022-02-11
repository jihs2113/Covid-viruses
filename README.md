# vu-covid-tracker

## Project setup
```
npm install
vue create  vu-covid-tracker
```

### using methods & grammer
```
fetch() / API / v-model / v-if v-else / v-for / 
@click / @change="onchange()"
this.@emit('')
find()
created()
numberWithCommas(x){
    return x.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ',')
    }
//글로벌적인 숫자같은것들을 바꿔주는것같다.
moment
computed:{
    timestamp: function(){
        return moment(this.dataDate).format('MMM do YYYY, h:mm:ss a')
    }
}

```

### tag
```
<select>
<option>

```