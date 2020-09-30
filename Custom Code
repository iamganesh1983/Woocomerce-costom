<?php
/**
 * Plugin Name: Custom Woo Shipping Zones
 * Plugin URI: https://htdestore.com
 * Author: Techiepress
 * Author URI:  https://htdestore.com
 * Description: Custom Woo Shipping Zones
 * Version: 0.1.0
 * License: GPL2 or Later.
 * License URL:  https://htdestore.com/
 * text-domain: prefix-plugin-name
*/

add_filter( 'woocommerce_states', 'techiepress_custom_shipping_zones' );

function techiepress_custom_shipping_zones( $states ) {
    
    $states['NP'] = array(
        'NP001' => 'Thamel',    
        'NP002' => 'Putalisadak',    
        'NP003' => 'Maitighar',    
    );
    
    return $states ;
}
