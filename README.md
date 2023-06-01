# mirai-tailwind-navwalker
This is custom nav_walker with tailwind classes and alpinejs attributtes.




//##########add to file en your folder ###########

//############setting wp_nav_menu ################
                                 
                                    
                                      //declarete the custom walker

                            $mwalker = new Mirai_Tailwind_Navwalker();
                           //setting menu
                            wp_nav_menu(array(             
                                'depth'	 => 2,
                                'walker' => $mwalker,
                                'container_class' => 'YOUR CLASS',
                                'menu_class' => 'YOUR CLASS',
                                'theme_location' => 'YOUR ID',
                                'before' => '',
                                'after' => '',
                            ))
                   
