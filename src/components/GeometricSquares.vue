<template>
    <div class="geometric-section-wrapper">
        <div class="message-wrapper">
            <h1>This will change</h1>
            <button @click="stuff()">Click Me</button>
            <div class="box" id="box"></div>
        </div>
        <div class="geometric-svg">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 849.41 849.4">
                <title>geometric-design</title>
                <g id="geometric-design">
                    <g id="row-1-col-1" class="one-one-hover">
                        <path id="blue-half-circle" class="cls-blue one-one-interest" d="M141.57,141.56A141.59,141.59,0,0,1,283.14,0V283.13A141.57,141.57,0,0,1,141.57,141.56Z"/>
                        <polygon id="red-triangle" class="cls-red" points="141.57 283.13 0.01 283.13 0.01 141.57 141.57 283.13"/>
                        <polygon id="green-triangle" class="cls-green" points="141.57 141.57 0.01 141.57 0.01 0 141.57 141.57"/>
                        <rect class="cls-background" width="283.14" height="283.14"/>

                    </g>
                    <g id="row-1-col-2">
                        <g id="corners">
                            <rect class="cls-blue" x="283.13" height="283.13"/>
                            <path class="cls-blue" d="M522.19,0a44.19,44.19,0,0,1,44.08,44.19V239a44.18,44.18,0,0,1-44.11,44.18h44.12V0Z"/>
                        </g>
                        <path id="red-half-circle" class="cls-red" d="M283.14,0H424.71V283.14A141.55,141.55,0,0,1,283.14,141.57Z"/>
                    </g>
                    <g id="row-1-col-3">
                        <path id="green-corner" class="cls-green" d="M849.4,283.13C849.4,126.77,722.65,0,566.27,0H849.4Z"/>
                        <path id="yelllow-half-circle" class="cls-yellow" d="M707.84,283.13H566.27V141.57A141.57,141.57,0,0,1,707.84,283.13Z"/>
                        <path id="red-half-circle-2" data-name="red-half-circle" class="cls-red" d="M849.4,283.13H707.84A141.57,141.57,0,0,0,566.27,141.57V0C722.65,0,849.4,126.77,849.4,283.13Z"/>
                    </g>
                    <g id="row-2-col-1">
                        <g id="green-lines">
                            <polygon class="cls-green" points="283.13 536.31 283.13 500.14 217.01 566.27 253.18 566.27 283.13 566.27 283.13 536.31"/>
                            <polygon class="cls-green" points="0 283.13 0 313.09 29.96 283.13 0 283.13"/>
                            <polygon class="cls-green" points="66.13 283.13 0 349.26 0 385.43 102.29 283.13 66.13 283.13"/>
                            <polygon class="cls-green" points="138.46 283.13 0 421.59 0 457.76 174.63 283.13 138.46 283.13"/>
                            <polygon class="cls-green" points="210.8 283.13 0 493.93 0 530.1 246.97 283.13 210.8 283.13"/>
                            <polygon class="cls-green" points="283.13 283.13 0 566.27 36.17 566.27 283.13 319.3 283.13 283.13"/>
                            <polygon class="cls-green" points="283.13 355.47 72.34 566.27 108.5 566.27 283.13 391.64 283.13 355.47"/>
                            <polygon class="cls-green" points="283.13 427.81 144.67 566.27 180.84 566.27 283.13 463.97 283.13 427.81"/>
                        </g>
                        <polygon id="yellow-triangle" class="cls-yellow" points="283.14 566.27 0.01 566.27 283.14 283.13 283.14 566.27"/>
                    </g>
                    <g id="row-2-col-2">
                        <path id="red-half-circle-3" data-name="red-half-circle" class="cls-red" d="M566.28,283.13c0,156.36-126.77,283.13-283.15,283.13V424.69A141.57,141.57,0,0,0,424.71,283.13Z"/>
                        <path id="green-corner-2" data-name="green-corner" class="cls-green" d="M424.71,283.13A141.56,141.56,0,0,0,283.14,424.69V283.13Z"/>
                    </g>
                    <g id="row-2-col-3">
                        <polygon id="green-triangle-2" data-name="green-triangle" class="cls-green" points="566.27 283.13 849.4 283.13 849.4 566.26 566.27 283.13"/>
                        <path id="blue-corner" class="cls-blue" d="M566.27,424.7V566.26H707.84A141.56,141.56,0,0,1,566.27,424.7Z"/>
                        <circle id="red-circle" class="cls-red" cx="707.84" cy="424.7" r="58.53" transform="translate(-92.99 624.91) rotate(-45)"/>
                    </g>
                    <g id="row-3-col-1">
                        <path id="blue-half-circle-2" data-name="blue-half-circle" class="cls-blue" d="M0,566.27H141.57V849.4A141.55,141.55,0,0,1,0,707.83Z"/>
                        <path id="red-half-circle-4" data-name="red-half-circle" class="cls-red" d="M283.14,849.4H141.57V566.27A141.54,141.54,0,0,1,283.14,707.83Z"/>
                    </g>
                    <g id="row-3-col-2">
                        <polygon id="green-triangle-3" data-name="green-triangle" class="cls-green" points="566.27 566.27 566.27 849.4 283.14 566.27 566.27 566.27"/>
                        <polygon id="yellow-triangle-2" data-name="yellow-triangle" class="cls-yellow" points="424.7 849.4 283.14 849.4 283.14 707.83 424.7 849.4"/>
                    </g>
                    <g id="row-3-col-3">
                        <path id="blue-half-circle-3" data-name="blue-half-circle" class="cls-blue" d="M707.84,849.39H566.27V707.83A141.57,141.57,0,0,1,707.84,849.39Z"/>
                        <path id="red-half-circle-5" data-name="red-half-circle" class="cls-red" d="M849.41,707.82V849.39H707.85A141.56,141.56,0,0,1,849.41,707.82Z"/>
                        <path id="yellow-half-circle" class="cls-yellow" d="M707.82,707.84A141.59,141.59,0,0,1,566.27,566.27H849.4A141.58,141.58,0,0,1,707.82,707.84Z"/>
                    </g>
                </g>
            </svg>
        </div>
    </div>

</template>

<script>
    import { TimelineLite } from 'gsap'
    export default {
        mounted() {
            this.timeline = new TimelineLite()
        },

        methods : {
            stuff() {
                this.timeline.to('#box', 1, { x: 200, rotation: 90 })
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    .geometric-svg {
        display: none;
    }

    .box {
        width: 50px;
        height: 50px;
        background: aquamarine;
    }
    .geometric-section-wrapper {
        display: grid;
        grid-template-columns: 1fr 1fr;
    }

    .geometric-svg {
        padding: 2rem;
    }

    .cls-background{
        fill: #435565;
        transform: translateX(50px);
        opacity: 0;
    }
    .cls-blue{fill:#435565;}
    .cls-red{fill:#de3e64;}
    .cls-green{fill:#a1c7a5;}
    .cls-yellow{fill:#eead70;}
    
    
    .one-one-interest {
        animation: one-one-interest 4s ease-in-out infinite;
    }
    
    @keyframes one-one-interest {
        50% {
            transform: translateX(.5rem) scale(.98);
        }
    }

    .one-one-hover:hover {
        cursor: pointer;
    }

    .focused .cls-background {
        animation: one-one-background .2s ease-in-out forwards;
    }

    @keyframes one-one-background {
        100% {
            transform: translateX(0px);
            opacity: 1;
        }
    }

    .one-one-hover:hover .cls-blue {
        transform: translateX(-50px);
        transition: .3s ease-out;
        /*opacity: .2;*/
    }

    .one-one-hover:hover .cls-red{
        /*transform: rotate(20deg);*/
        /*transform-origin: bottom left;*/
    }
</style>
