A simple repo to track a Puppefile with the puppetmodules I work on so that librarian-puppet can pull them.

Quick start:

      gem install librarian-puppet
      cd puppet_control
      librarian-puppet install
      puppet apply test_manifest.pp --modulepath=./modules