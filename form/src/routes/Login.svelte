<script>
    import {goto} from '$app/navigation';
    import {writable} from '$svelte/store';

    let username = '';
    let email = '';
    let password = '';
    let confirmedPassword = '';
    let formErrors = [];
    
</script>