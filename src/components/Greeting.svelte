<script lang="ts">
    const curretTime = new Date()
    const currentHour = curretTime.getHours()

    let greetig = ''

    if (currentHour<12){
        greetig = 'Buenos Días'
    } else if (currentHour < 18){
        greetig = 'Buenas Tardes'
    } else {
        greetig = 'Buenas Noches'
    }
</script>

<h1 class="text-4xl font-bold ">{greetig}</h1>