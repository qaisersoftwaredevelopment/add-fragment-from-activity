# add-fragment-from-activity
 MountainerClimber_fragment mountainerClimber_fragment = new MountainerClimber_fragment();         FragmentManager fm = getSupportFragmentManager();         FragmentTransaction transaction = fm.beginTransaction();         transaction.replace(R.id.mountain_climber_contianer, mountainerClimber_fragment);         transaction.commit();
