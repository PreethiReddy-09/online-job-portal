<template>
    <footer class="footer-container">
        <div class="contact-us">
            <p>About Us</p>
            <p>|</p>
            <p>Contact Us</p>
            <p>|</p>
            <p>Email: info@jobportal.com</p>
        </div>
        <div class="social-media-links">
            <img class="img" src="https://static.vecteezy.com/system/resources/previews/022/257/063/non_2x/icon-media-social-facebook-free-vector.jpg" alt="facebook">
            <img class="img" src="https://img.freepik.com/premium-vector/twitter-new-x-logo-design-vector_1340851-70.jpg?semt=ais_hybrid" alt="x">
            <img class="img" src="https://icons.veryicon.com/png/o/miscellaneous/offerino-icons/instagram-53.png" alt="instagram">
            <img class="img" src="https://icons.veryicon.com/png/o/photographic/ant-design-official-icon-library/youtube-118.png" alt="youtube">
            <img class="img" src="https://icons.veryicon.com/png/o/miscellaneous/offerino-icons/pinterest-67.png" alt="pintrest">
        </div>
    </footer>
</template>
    
    <script>
    
    export default{
        name: 'FooterComponent',
        props:{ 
            // appName:String
        }
    }
    
    </script>
    
    <style scoped>

    .footer-container{
        padding: 1rem;
        margin: 0.5rem 0;
        background-color: #000;
        color: #FFF;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .img{
        background-color: #FFF;
        border-radius: 50%;
        width: 20px;
        height: 20px;
    }

    .contact-us, .social-media-links{
        display: flex;
        gap: 1rem;
        font-size: 14px;
    }
    
    </style>