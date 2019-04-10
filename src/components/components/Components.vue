<template>
    <div>
        <navbar></navbar>
        <sidebar></sidebar>
        <contents></contents>
    </div>
</template>


<script>
import Navbar from '@/components/components/layout/Navbar'
import Sidebar from '@/components/components/layout/Sidebar'
import Contents from '@/components/components/layout/Contents'
export default {
    components: {
        'navbar': Navbar,
        'sidebar': Sidebar,
        'contents': Contents,
    }
}
</script>
