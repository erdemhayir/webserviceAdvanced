package org.erdem.advanced.rest;

import javax.inject.Singleton;
import javax.ws.rs.GET;
import javax.ws.rs.Path;
import javax.ws.rs.Produces;
import javax.ws.rs.core.MediaType;

@Path("test")
@Singleton
public class MyResource {
	private int count;
	@GET
	@Produces(MediaType.TEXT_PLAIN)
	public String testMethod(){
		count++;
		return "it works. This method called "+count+" time(s)";
	}
}
