<?php

/*
Plugin Name: Page Loading Effect
Description: This plugin adds beautiful effect while page is loading
Version: 1.0
Author: Santo
License: GPL2

Copyright 2013  PACE Pro  (email : santo@explorehowto.com)

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License, version 2, as
published by the Free Software Foundation.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA

*/
function pace_bluescript() {
                    wp_register_script('pacescript', 'http://cdnjs.cloudflare.com/ajax/libs/pace/0.6.0/pace.min.js', false);
                    wp_enqueue_script( 'pacescript' );
            }
            add_action('wp_enqueue_scripts', 'pace_bluescript');

function pace_bluecss() {
                wp_register_style( 'pacebluecss', 'http://cdnjs.cloudflare.com/ajax/libs/pace/0.6.0/themes/blue/pace-theme-loading-bar.css' );
                wp_enqueue_style( 'pacebluecss' );
            }
            add_action( 'wp_enqueue_scripts', 'pace_bluecss' );
?>
