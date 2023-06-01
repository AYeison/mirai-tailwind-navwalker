# mirai-tailwind-navwalker
This is custom nav_walker with tailwind classes and alpinejs attributtes.




//##########add to file###########
   
require get_template_directory() . '/src/tailwind-navwalker.php';

//############setting wp_nav_menu ################
     
                            $mwalker = new Mirai_Tailwind_Navwalker();

                            wp_nav_menu(array(             
                                'depth'	 => 2,
                                'walker' => $mwalker,
                                'container_class' => 'YOUR CLASS',
                                'menu_class' => 'YOUR CLASS',
                                'theme_location' => 'YOUR ID',
                                'before' => '',
                                'after' => '',
                            ))
                   
