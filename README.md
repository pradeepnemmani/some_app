# commands

					<tr>
				 		<td>
				 			<% @microposts.each do |micropost| %>s
				 		</td>
				 		<td>
				 			<%=link_to micropost.name, micropost %>
				 		</td>
				 		<td>
							<%=link_to "delete", micropost, :method => :delete,
																
				 		</td>
				 		<td>
				 			<%=link_to "edit", edit_micropost_path(micropost)%>
				 		</td>
				 	</tr>
