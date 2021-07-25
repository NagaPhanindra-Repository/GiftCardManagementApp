# GiftCardManagementApp
Spring Boot Micro service with Angular App
	
	@Override
	protected void configure(HttpSecurity http)throws Exception {
		http.csrf().
        disable()
            .authorizeRequests()
            .antMatchers("/GiftCardManagement/api/v1/HealthStatus").permitAll()
            .antMatchers(HttpMethod.OPTIONS, "/**")
            .permitAll()
            .anyRequest()
            .authenticated()
            .and()
            .httpBasic();
		
