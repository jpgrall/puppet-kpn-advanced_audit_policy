source ENV['GEM_SOURCE'] || "https://rubygems.org"

# An update in rake 11.0.0 breaks stuff.
# Removed Rake::TaskManager#last_comment. Use last_description.
# RSPEC
group :test do
  gem 'diff-lcs', '~> 1.3.0'
  gem 'kpn-style'
  gem 'metaclass', '~> 0.0.4'
  gem 'metadata-json-lint', '~> 1.1.0'
  gem 'mocha', '~> 1.2.1'
  gem 'puppet', ENV['PUPPET_VERSION'] || '4.8.2'
  gem 'puppet-lint', '2.2.1'
  gem 'puppet-syntax', '~> 2.4.0'
  gem 'puppetlabs_spec_helper', '~> 2.1.1'
  gem 'rake', '~> 12.0.0'
  gem 'rspec', '~> 3.5.0'
  gem 'rspec-core', '~> 3.5.4'
  gem 'rspec-expectations', '~> 3.5.0'
  gem 'rspec-mocks', '~> 3.5.0'
  gem 'rspec-puppet', '~> 2.5.0'
  gem 'rspec-puppet-utils', '~> 3.1.0'
  gem 'rspec-support', '~> 3.5.0'
  gem 'spdx-licenses', '~> 1.1.0'
  gem 'puppet-lint-absolute_classname-check', '~> 0.2.4'
  gem 'puppet-lint-classes_and_types_beginning_with_digits-check', '~> 0.1.2'
  gem 'puppet-lint-file_ensure-check', '~> 0.3.1'
  gem 'puppet-lint-leading_zero-check', '~> 0.1.1'
  gem 'puppet-lint-spaceship_operator_without_tag-check', '~> 0.1.1'
  gem 'puppet-lint-trailing_comma-check', '~> 0.3.2'
  gem 'puppet-lint-undef_in_function-check', '~> 0.2.1'
  gem 'puppet-lint-unquoted_string-check', '~> 0.3.0'
  gem 'puppet-lint-version_comparison-check', '~> 0.2.1'
  gem 'puppet-lint-variable_contains_upcase', '~> 1.2.0'
  gem 'puppet-lint-absolute_template_path', '~> 1.0.1'
  gem 'puppet-lint-trailing_newline-check', '~> 1.1.0'
  gem 'puppet-lint-file_source_rights-check', '~> 0.1.1'
  gem 'puppet-lint-resource_reference_syntax', '~>1.0.10'
  gem 'puppet-lint-package_ensure-check', '~>0.2.0'
  gem 'puppet-lint-duplicate_class_parameters-check', '~>1.0.2'
end