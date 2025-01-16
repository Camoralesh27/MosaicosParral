@mixin phone {
    @media screen and (width >= v.$phone){
        @content;
    }
}

@mixin tablet {
    @media screen and (v.$phone <= width <= v.$tablet){
        @content;
    }
}

@mixin desktop {
    @media screen and (width <= v.$desktop){
        @content;
    }
}