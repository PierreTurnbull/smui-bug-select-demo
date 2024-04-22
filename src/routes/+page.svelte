<script>
    import Select from "@smui/select";
    import { Modal } from "flowbite-svelte"

    let flowbiteOpen = true
</script>
<Modal
    open={flowbiteOpen}
>
    flowbite modal
    <Select></Select>
    <button on:click={() => flowbiteOpen = false}>close dialog</button>
</Modal>