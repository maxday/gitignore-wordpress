gitignore-wordpress
===================

# We don't need core files ... so let's ignore them, we just need th wp-content directory
/*
!.gitignore
!wp-content/

# We just need plugins and themes directory 
wp-content/*
!wp-content/plugins/
!wp-content/themes/
