if RUBY_VERSION < '2.0'
  appraise '3.0' do
    gem 'rails', '~> 3.0.17'
  end

  appraise '3.1' do
    gem 'rails', '~> 3.1.8'
    gem 'jquery-rails'
    gem 'sass-rails'
  end
end

appraise '3.2' do
  gem 'rails', '~> 3.2.13'
  gem 'jquery-rails'
  gem 'sass-rails'
end

if RUBY_VERSION >= '1.9.3'
  appraise '4.0' do
    gem 'rails', '~> 4.0.0'
    gem 'protected_attributes'
  end
end
