<template>
    <li v-for="value in myObject">
    {{ value.name }}
    </li>
</template>

<script>
export default {
data() {
return {
    myObject: [
        {
        name: 'Banana',
        description: 'Description of the product',
        price: 1,
        quantity: 1,
        image: 'https://www.primefaces.org/wp-content/uploads/2020'
    },
        {
        name: 'Strawberries',
            description: 'Description of the product',
            price: 2,
            quantity: 2,
            image: 'https://www.primefaces.org/wp-content/uploads/2020'
        },
        {
            name: 'Melons',
            description: 'Description of the product',
            price: 3,
            quantity: 3,
            image: 'https://www.primefaces.org/wp-content/uploads/2020'
        },
        {
            name: 'Kiwi',
            description: 'Description of the product',
            price: 4,
            quantity: 4,
            image: 'https://www.primefaces.org/wp-content/uploads/2020'
        
        },
    ],
};
}
}

</script>

<style scoped>

</style>