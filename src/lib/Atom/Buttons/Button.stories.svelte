<script>
    import { Meta , Template , Story } from '@storybook/addon-svelte-csf';
    import Button from './Button.svelte';
</script>

<Meta 
    title="Design/Atoms/Buttons"
    component={Button}
    argTypes={{
        label:{control:'text'},
        primary:{control:'boolean'},
        onClick:{action:'clicked button'}
    }}
/>

<Template let:args>
    <Button {...args} />
</Template>

<Story 
    name="Basic"
/>