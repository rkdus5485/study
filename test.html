<%@ page language="java" contentType ="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ page import = "java.sql.*"%>
<%@ page import = "java.sql.DriverManager" %>
<%@ page import = "java.sql.Connection" %>
<%@ page import = "java.sql.Statement" %>
<%@ page import = "java.sql.PreparedStatement"%>
<%@ page import = "java.sql.ResultSet" %>
<%@ page import = "java.sql.SQLException" %>
<%@ page import = "java.io.PrintWriter" %>
<%		
		
		Connection conn = null;
		Statement stmt = null;
		ResultSet rs = null;
		PreparedStatement ps = null;
		

		try{
			String jdbcDriver = "jdbc:mysql://localhost:3306/test"
				+"?useUnicode=true&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=UTC";
			String dbUser = "root";
			String dbPass = "5485";
			Class.forName("com.mysql.jdbc.Driver");
			
			conn = DriverManager.getConnection(jdbcDriver, dbUser, dbPass);

			%>
	<!doctype html>
		<html lang="en">
		<head>
			<meta charset="UTF-8">
		</head>
		<body>
			<div>
			<%	ps= conn.prepareStatement("select name, age from test;");
				rs=ps.executeQuery();

				while(rs.next()){

					String name= rs.getString("name");
					String age= rs.getString("age");


		%>
				<tr>
					<td>
						이름
					</td>
					<td>
						나이
					</td>
					
				</tr>
				<tr>
					<td>
						<%=name%>
					</td>
					<td>
						<%=age%>
					</td>
				</tr>
			</div>
		</body>

	<%
		}
		}finally{
				if(rs != null) try{rs.close();}catch(SQLException ex){}
		if(stmt != null) try{stmt.close();} catch(SQLException ex){}
		if(conn != null) try{conn.close();} catch(SQLException ex){}
			}%>
		</html>
