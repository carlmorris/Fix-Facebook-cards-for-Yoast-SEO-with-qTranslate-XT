<?php
/*
Plugin Name: Fix Facebook cards for Yoast SEO with qTranslate XT
Plugin URI: https://morris.cymru
description: This WordPress plugin fixes a Facebook cards problem when running qTranslateXT and Yoast SEO. The problem is that Facebook cards always display in the default language for all language URLs. This plugin ensures that the cards display in the correct language. It achieves this by rewriting the og:url metatag. Other cards e.g. Twitter are unaffected. Tested with qTranslate-XT 3.8.1 and Yoast 14.7 
Version: 1.0
Author: Carl Morris
Author URI: https://morris.cymru
License: GPL2
*/

add_filter( 'wpseo_opengraph_url', 'change_url' );

function change_url( $url )
{
  $url = get_permalink();
  return $url;
}
