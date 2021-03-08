# Landing Page

A simple starter landing page

## Description

This uses a jQuery countdown timer embedded on a landing page and is just a simple way to get something on a hosted site until you are ready to start production.

### Dependencies

Bootstrap 4 with all the other dependencies such as jQuery and Popper and Google Fonts

### Installing

All files and folders need to be transferred to wherver you are hosting  Then the script code in the index.html can be modified to your future date:
<script>
        $(function() {
            $('.countdown').countdown({
                date: "June 7, 2021 15:03:26"
            });
        });
    </script>