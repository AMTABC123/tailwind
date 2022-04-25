<script>
    import { Plus, LightningFill, GearFill } from 'svelte-bootstrap-icons';
    import FaFire from 'svelte-icons/fa/FaFire.svelte';
    import FaSmile from 'svelte-icons/fa/FaSmile.svelte'
    import SidebarIcon from "./SidebarIcon.svelte";
</script>

<div class="fixed top-0 left-0 h-screen w-16 m-0 flex flex-col bg-primary text-secondary shadow-lg">
    <SidebarIcon>
        <FaFire />
    </SidebarIcon>

    <SidebarIcon>
        <Plus />
    </SidebarIcon>

    <SidebarIcon>
        <LightningFill />
    </SidebarIcon>

    <SidebarIcon>
        <FaSmile />
    </SidebarIcon>
</div>