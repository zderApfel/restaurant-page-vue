<template>
    <div id="menu">
        <h1>{{ msg }}</h1>
        <table>
            <tr>
                <th>
                    <figure>
                        <img alt="A normal borger" src="../assets/normal-borger.jpeg">
                        <figcaption>Borger - $12.50</figcaption>
                    </figure>
                </th>
                <th>
                    <figure>
                        <img alt="A soopreme borger" src="../assets/supreme-borger.jpg">
                        <figcaption> Supreme Borger - $18.00</figcaption>
                    </figure>
                </th>
            </tr>
            <tr>
                <th>
                    <figure>
                        <img alt="Fronch Frys" src="../assets/fronch-fries.jpg">
                        <figcaption>Fronch Frys - $5.50</figcaption>
                    </figure>
                </th>
                <th>
                    <figure>
                        <img alt="Various Soders" src="../assets/soder.jpeg">
                        <figcaption>Soder (Conk Products) - $1.27</figcaption>
                    </figure>
                </th>
            </tr>
        </table>
    </div>
</template>

<script>
export default {
    name: "MenuContent",
    props:{
        msg: String
    }
}
</script>

<style scoped>

html {
    padding: 0;
    margin: 0;
}

h1 {
    padding: auto;
    margin: auto;
}

table {
    margin: auto;
    padding: auto;
}

img {
    width: 250px;
    height: 150px;
}

</style>